---
layout: about
title: about
permalink: /
subtitle: <a href="#">My Portfolio</a>

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Inchoen, South Korea</p>
    <p><i class="fa-solid fa-envelope"></i> <a href="mailto:busymonaz@gmail.com">busymonaz@gmail.com</a></p>

selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 3 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: true
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

<div class="content-box">

  <h3>💻 Tech Stack & Interests</h3>

  <div style="margin-top: 15px;">
    <span class="tech-badge">Python</span>
    <span class="tech-badge">JavaScript</span>
    <span class="tech-badge">C++</span>
    <span class="tech-badge">React</span>
    <span class="tech-badge">FastAPI</span>
    <span class="tech-badge">PyTorch</span>
  </div>
  
  <ul style="margin-top: 20px; list-style-type: '📂 ';">
    <li><strong>Interests:</strong> Machine Learning, Backend Engineering, Scalable Systems</li>
  </ul>
</div>

<div class="content-box" style="border-left-color: #d2b48c;"> 

  <p>개발자가 되기 위해 공부하고 있는 <strong>모나</strong>입니다.</p>
  <p>이 블로그에는 제가 공부하며 깊게 고민한 내용과 삽질의 기록들이 올라옵니다. 🛠️</p>
  
</div>

<div class="content-box">
  {% if site.latest_posts.enabled -%}
    <h2><a href="{{ '/blog/' | relative_url }}" style="color: inherit;">Latest Posts</a></h2>
    {% include latest_posts.liquid %}
  {%- endif %}
</div>