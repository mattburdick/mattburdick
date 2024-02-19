# My Projects
List of my projects
# My interests
Literally None
# My blog
I'm excited to blog my journey on GitHub.com
<ul>
{% for post in site.posts %}
<li>
<a href="{{ post.url }}">{{ post.title }}</a>
</li>
{% endfor %}
</ul>
# Get in touch
<ul>
    <li><a href="https://linkedin.com/in/{{ site.linkedin_username}}">LinkedIn</a></li>
    <li><a href="https://github.com/{{ site.github_username}}">GitHub</a></li>
</ul>


