<!-- https://mattburdick.github.io/mattburdick/ -->

---
layout: default
title: "Home"
---

{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="Posts" %}
{% endif %}
<!-- # My Projects
List of my projects go here
# My interests
Literally None
# My blog
I'm excited to blog my journey on GitHub.com
<ul>
{% for post in site.posts %}
<li>
<a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
</li>
{% endfor %}
</ul>
# Get in touch
<ul>
    <li><a href="https://linkedin.com/in/{{ site.linkedin_username}}">LinkedIn</a></li>
    <li><a href="https://github.com/{{ site.github_username}}">GitHub</a></li>
</ul>
# Testing postlinking
<p>See this post <a href="https://www.linkedin.com/posts/adamhobson_newjob-zoox-onezoox-activity-7153502722258862080-hOIm?utm_source=share&utm_medium=member_desktop">on LinkedIn</a></p> -->


