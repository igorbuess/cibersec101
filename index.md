---
layout: default
---

Esta página tem como objetivo disseminar conhecimentos e boas práticas de segurança digital por meio de conteúdo prático, acessível e baseado em experiências do mundo real. O foco é auxiliar usuários com conhecimentos básicos e intermediários em tecnologia a compreender riscos, adotar medidas de proteção e utilizar recursos digitais de forma mais segura.

## Artigos

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
