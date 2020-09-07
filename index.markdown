---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default 
---

# Zines for Portlanders

### (and everyone else, too)


{% for post in site.tags.zine %}
  <h2><a href="{{ post.url }}">{{post.prefix}} {{ post.vol}}: {{ post.title }}</a></h2>

  *{{ post.date | date: '%B %d, %Y' }}*

  {{ post.description }}
{% endfor %}

{% include footer.html %}
