---
layout: default
title: Welcome
---

# 👋 Olá!

seja bem vindo ao repositório do Núcleo Web para a Comunicação.

Abaixo fica uma lista dos nossos repositórios:

## 📂 Repositórios

<ul>
  {% for repo in site.github.public_repositories %}
    <li>
      <a href="{{ repo.html_url }}">{{ repo.name }}</a>: {{ repo.description }}
    </li>
  {% endfor %}
</ul>
git remote add origin https://github.com/scml-uacor-nwc/scml-uacor-nwc.git