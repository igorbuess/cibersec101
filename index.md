---
layout: default
---

# Cibersegurança 101

Sou Igor Buess, graduado em Engenharia da Computação e pós-graduado em Segurança da Informação e Inteligência Artificial Aplicada. Atuo na área de Cibersegurança, contribuindo para o fortalecimento da segurança da informação em organizações de diversos segmentos.

Esta página foi criada para disseminar conhecimentos e boas práticas de segurança digital por meio de uma linguagem clara e acessível, auxiliando pessoas a reduzirem riscos e a utilizarem a tecnologia de forma mais segura.

O conteúdo é direcionado principalmente a usuários com conhecimentos básicos ou intermediários em tecnologia, que podem se beneficiar de orientações práticas para o dia a dia digital.

## Artigos

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
