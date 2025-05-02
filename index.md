---
layout: default
title: Núcleo Web para a Comunicação
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
  <li>
</ul>

## 🔒 Private Projects

- [SHR](https://github.com/scml-uacor-nwc/simple-history-reader): Simple History Reader
- [CCM](https://github.com/scml-uacor-nwc/scml-ccm): Cookie Consent Management
- [PLD](https://github.com/scml-uacor-nwc/Plugin-List-Display) Plugin List Display