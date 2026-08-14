---
title: "Contact"
permalink: /contact/
layout: single
author_profile: true
---
I work with athletes, coaches, and organizations to design performance testing, monitoring, and analytics systems grounded in applied sport science.

If you are reaching out about a project or consultation, please include a brief description below so I can respond appropriately.

You can also email me directly at [{{ site.email }}](mailto:{{ site.email }}).

---

<form id="contact-form" action="https://formspree.io/f/mkgldqev" method="POST">
  <input type="hidden" name="_subject" value="Website performance consultation inquiry">

  <div class="form-field">
    <label for="name">Name</label>
    <input type="text" id="name" name="name" autocomplete="name" required>
  </div>

  <div class="form-field">
    <label for="email">Email</label>
    <input type="email" id="email" name="_replyto" autocomplete="email" required>
  </div>

  <div class="form-field">
    <label for="project_type">Project type</label>
    <select id="project_type" name="project_type" required>
      <option value="">Select one</option>
      <option value="team_analytics">Team performance analytics</option>
      <option value="individual_support">Individual athlete support</option>
      <option value="testing_monitoring">Testing & monitoring setup</option>
      <option value="dashboards_tools">Dashboards or data tools</option>
      <option value="research_collaboration">Research / collaboration</option>
      <option value="other">Other / Exploratory</option>
    </select>
  </div>

  <div class="form-field">
    <label for="timeline">Proposed timeline</label>
    <select id="timeline" name="timeline">
      <option value="">Optional</option>
      <option value="immediate">Immediate / urgent</option>
      <option value="1_3_months">1–3 months</option>
      <option value="3_plus_months">3+ months</option>
    </select>
  </div>

  <div class="form-field">
    <label for="message">Brief description</label>
    <textarea
      id="message"
      name="message"
      rows="6"
      placeholder="Describe the problem you're trying to solve or the outcome you're aiming for"
      required
    ></textarea>
  </div>

  <button type="submit" class="btn btn--primary">Send message</button>

  <p class="form-note">
    Typical response within 48 hours.  
    Your information is used only to reply to your inquiry.
  </p>

</form>
