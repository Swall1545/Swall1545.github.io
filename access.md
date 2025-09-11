---
title: Request Code Access
permalink: /access/
---
# Request Code Access

To comply with academic policies, project code lives in **private GitHub repositories**.
Please request **read-only** access using the form below.

> You’ll need your **GitHub username** and the **project names** you want to review.

<form action="https://formspree.io/f/mwpnyzwl" method="POST" autocomplete="on">
  <!-- Optional: redirect to a thank-you page on your site -->
  <input type="hidden" name="_redirect" value="https://swall1545.github.io/access/thanks/">
  <input type="hidden" name="_subject" value="Code access request from portfolio">

  <div style="display:grid; gap:12px; grid-template-columns:repeat(auto-fit,minmax(260px,1fr));">
    <label>Your Name
      <input name="name" type="text" required>
    </label>
    <label>Company
      <input name="company" type="text" required>
    </label>
    <label>Company email (required)
      <input name="company_email" type="email" required placeholder="name@company.com">
    </label>
    <label>GitHub username (required)
      <input name="github_username" type="text" required>
    </label>
    <label>LinkedIn URL (required)
      <input name="linkedin_url" type="url" required placeholder="https://linkedin.com/in/your-profile">
    </label>
  </div>

  <p style="font-size:.9rem;opacity:.8;margin:.5rem 0 0;">
    Company email domain should match the company named above. If there’s a mismatch—or if you’d like confirmation I received your request—please DM me on LinkedIn.
  </p>

  <fieldset style="margin:1rem 0;">
    <legend><strong>Projects requested (select all that apply)</strong></legend>
    <label><input type="checkbox" name="projects[]" value="D682 — Air Quality Forecasting"> D682 — Air Quality Forecasting</label><br>
    <label><input type="checkbox" name="projects[]" value="D797 — Alzheimer’s Prevalence"> D797 — Alzheimer’s Prevalence</label><br>
    <label><input type="checkbox" name="projects[]" value="MLIR Operator Fusion Proposal"> MLIR Operator Fusion Proposal</label><br>
    <label><input type="checkbox" name="projects[]" value="D795 — Emergency Dispatch Optimization"> D795 — Emergency Dispatch Optimization</label><br>
    <label><input type="checkbox" name="projects[]" value="WGUPS Routing"> WGUPS Routing</label><br>
    <label><input type="checkbox" name="projects[]" value="Fortran → Python Port"> Fortran → Python Port</label><br>
    <label><input type="checkbox" name="projects[]" value="D287 — Java Frameworks (Spring MVC)"> D287 — Java Frameworks (Spring MVC)</label><br>
    <label><input type="checkbox" name="projects[]" value="D288 — Angular Front End"> D288 — Angular Front End</label><br>
    <label><input type="checkbox" name="projects[]" value="D387 — Advanced Java (Spring REST + Angular)"> D387 — Advanced Java (Spring REST + Angular)</label><br>
    <label><input type="checkbox" name="projects[]" value="C867 — C++ Class Roster"> C867 — C++ Class Roster</label>
  </fieldset>

  <fieldset style="margin:1rem 0;">
    <legend><strong>Purpose</strong></legend>
    <label><input type="radio" name="purpose" value="Hiring review" required> Hiring review</label><br>
    <label><input type="radio" name="purpose" value="Technical screening"> Technical screening</label><br>
    <label><input type="radio" name="purpose" value="Team evaluation"> Team evaluation</label><br>
    <label><input type="radio" name="purpose" value="Other"> Other</label>
  </fieldset>

  <label>Notes (optional)
    <textarea name="notes" rows="3" placeholder="Anything else you'd like me to know."></textarea>
  </label>

  <!-- Honeypot (spam trap) -->
  <label style="display:none">Website
    <input name="website" type="text" tabindex="-1" autocomplete="off">
  </label>
  <br>
  <p style="font-size:.9rem;opacity:.8">
    I’ll add your GitHub account as a temporary <strong>read-only</strong> collaborator to the requested repositories.
    <strong>There is no redirect on this page once you submit.</strong>
  </p>

  <button type="submit">Request access</button>
</form>

