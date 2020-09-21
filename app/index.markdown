---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

{% for tip in site.tips %}
  <h2>
    <a href="{{ site.baseurl }}{{ tip.url }}">
      {{ tip.title }}
    </a>
  </h2>
  {{ tip.description }}
{% endfor %}
