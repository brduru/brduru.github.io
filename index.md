---
title: "Início"
---

# Artigos

{% if site.posts.size > 0 %}
{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%d/%m/%Y" }}
{% endfor %}
{% else %}
Nenhum artigo publicado ainda.
{% endif %}
