---
layout: home
permalink: /
profile_picture:
  src: /assets/img/profile-pic.jpg
  alt: website picture
---

# Hi, I'm Jeongin Park
Aspiring PhD candidate in Computer Science, dedicated to bridging the gap between AI and human interaction. 

I'm currently an undergraduate student in Seoul National University, fully funded by Presidential Science Scholarship. 

Feel free to check out my work and experience!

<!-- Social & Contact Links -->
<div class="contact-links">
  <a href="mailto:parkjeong02@gmail.com" title="Email">
    <i class="fas fa-envelope"></i>
  </a>
  <a href="https://github.com/ZzeongB" target="_blank" title="GitHub">
    <i class="fab fa-github"></i>
  </a>
  <a href="{{ item.cv | relative_url }}" target="_blank" title="Download CV">
      CV
    </a>
</div>

<div id="education">
<h3 class="section">Education</h3>
<hr>
{% include education.html %}
</div>


<div id="experience">
<h3 class="section">Experience</h3>
<hr>
{% include experience.html %}
</div>

<div id="all-projects">
<h3 class="section">Featured Works</h3>
<hr>
{% include all-projects.html %}
</div>