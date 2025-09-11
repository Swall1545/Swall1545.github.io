---
title: Request Code Access
permalink: /access/
---
# Request Code Access

To comply with academic policies, project code lives in **private GitHub repositories**.
Please request **read-only** access using the form below.

> You’ll need your **GitHub username** and the **project names** you want to review.

<form action="https://formspree.io/f/mwpnyzwl" method="POST" autocomplete="on">
  <!-- (Optional) redirect to a thank-you page after submit -->
  <input type="hidden" name="_redirect" value="https://swall1545.github.io/access/thanks/">
  <!-- Email subject you’ll receive -->
  <input type="hidden" name="_subject" value="Code access request from portfolio">

  <div style="display:flex; gap:12px; flex-wrap:wrap">
    <label style="flex:1 1 260px">Name
      <input name="name" type="text" required>
    </label>

    <label style="flex:1 1 260px">Company / Role
      <input name="company_role" type="text">
    </label>

    <label style="flex:1 1 260px">GitHub username (required)
      <input name="github_username" type="text" required>
    </label>

    <label style="flex:1 1 260px">LinkedIn URL (required)
      <input name="linkedin_url" type="url" required placeholder="https://linkedin.com/in/...">
    </label>

    <label style="flex:1 1 100%">Projects requested (required)
      <input name="projects" type="text" required placeholder="e.g., D682 Air Quality; D797 Alzheimer’s; D795 Dispatch">
    </label>

    <label style="flex:1 1 100%">Purpose (1–2 sentences)
      <textarea name="purpose" rows="3" placeholder="Hiring review, technical screen, etc."></textarea>
    </label>

    <label style="flex:1 1 260px">Your email (for invite)
      <input name="requester_email" type="email" placeholder="name@company.com">
    </label>

    <!-- Honeypot (spam trap) -->
    <label style="display:none">Website
      <input name="website" type="text" tabindex="-1" autocomplete="off">
    </label>
  </div>

  <p style="font-size:.9rem;opacity:.8">
    I’ll add your GitHub account as a temporary <strong>read-only</strong> collaborator to the requested repositories.
    <strong>There is no redirect on this page once you submit.</strong>
  </p>

  <button type="submit">Request access</button>
</form>
