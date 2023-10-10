---
layout: default
title: Rodica's blog
---
<html>
  <head>
    <meta charset="utf-8">
    <title>{{ page.title }}</title>
  </head>
  <body>
    <div class="main">
      <h1>{{ "Rodica's blog" | downcase }}</h1>
      {% for post in site.posts %}
        {% include article-summary.html %}
      {% endfor %}
    </div>
    {% include categorie-list.html %}
  </body>
</html>

