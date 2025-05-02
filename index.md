---
layout: default
title: Núcleo Web para a Comunicação
---

# 👋 Olá!!!

Bem-vindo ao repositório de projetos do Núcleo Web para a Comunicação (NWC), uma iniciativa da Unidade de Aplicações Corporativas (UACOR) da Direção de Sistemas e Tecnologias de Informação (DISTI) da Santa Casa da Misericórdia de Lisboa.

Explora os projetos e soluções que ligam pessoas, promovem a inclusão e potenciam a comunicação institucional.

## 📂 Repositórios de livre acesso

<ul>
  {% for repo in site.github.public_repositories %}
    <li>
      <a href="{{ repo.html_url }}">{{ repo.name }}</a>: {{ repo.description }}
    </li>
  {% endfor %}
</ul>

## 🔒 Projects Privados

<ul>
<li><a href="https://github.com/scml-uacor-nwc/simple-history-reader">Simple History Reader [SHR]</a></li>
<li><a href="https://github.com/scml-uacor-nwc/scml-ccm">Cookie Consent Management [CCM]</a></li>
<li><a href="https://github.com/scml-uacor-nwc/Plugin-List-Display">Plugin List Display</a></li>
</ul>


