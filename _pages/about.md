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

<div class="main-content-wrapper">

## 🛠 Tech Stack & Interests

전문성을 기르기 위해 주로 사용하는 기술들입니다.

<div style="margin: 20px 0;">
  <span class="tech-badge">Python</span>
  <span class="tech-badge">JavaScript</span>
  <span class="tech-badge">C++</span>
  <span class="tech-badge">React</span>
  <span class="tech-badge">FastAPI</span>
  <span class="tech-badge">PyTorch</span>
</div>

**Focus:** Machine Learning, Backend Engineering, Scalable Systems

---

## ✍️ About Me

개발자가 되기 위해 끊임없이 공부하고 고민하는 **모나**입니다.  
단순히 코드를 짜는 것을 넘어, 효율적인 시스템과 사용자 경험에 대해 깊이 있게 탐구합니다.

이 공간에는 제가 공부하며 마주한 기술적 고민들과 그 과정을 해결해 나간 삽질의 기록들을 차곡차곡 쌓아가고 있습니다. 🛠️

---

## 📮 Latest Posts

블로그의 최신 글들을 확인해 보세요.

{% if site.latest_posts.enabled -%}
  <div style="margin-top: 30px;">
    {% include latest_posts.liquid %}
  </div>
{%- endif %}

</div>

<!-- <div class="content-box">
  {% if site.latest_posts.enabled -%}
    <h2><a href="{{ '/blog/' | relative_url }}" style="color: inherit;">Latest Posts</a></h2>
    {% include latest_posts.liquid %}
  {%- endif %}
</div> -->