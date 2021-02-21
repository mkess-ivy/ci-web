---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: theme002
bg-img: /img/ci-bg.jpg
---
{% include page_title.html name="Culture Intersects" desc="save black futures" %}

{% for item in site.portfolio %}
{{ item.header }}
{{ item.title }} 
{% endfor %}