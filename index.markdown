---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

# Jonathan Bell

This new version of my website is VERY under construction. I'll be writing posts about my process as I build it out, so read below to get a sense of what's going on here (and why things look so bland currently).

## Posts
{% for post in site.posts %}
[{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}