---
title: Portfolio
icon: fa-th
order: 3
---

I have completed projects in a variety of different languages, including Python3, Java, and Swift

#### Featured Projects
{% assign featured = site.projects | sample: 3 %}

<div class="row">
{% for project in featured %}
  <div class="4u 12u$(mobile)">
    <div class="item">
      <a href="projects/#{{ project.title | slugify }}" class="image fit"><img src="{{ project.preview | relative_url }}" alt="{{ project.title }}" /></a>
      <a href="projects/#{{ project.title | slugify }}">
        <header>
          <h3>{{ project.title }}</h3>
        </header>
      </a>
    </div>
  </div>
{% endfor %}
