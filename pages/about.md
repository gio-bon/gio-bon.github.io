---
layout: page
title: Sobre
permalink: /about/
weight: 3
---

# **Sobre mim**

Olá, sou o **{{ site.author.name }}** :wave:,<br>
Trabalho como desenvolvedor e sou formado em Tecnologia da Informação. Tenho interesse em cloud e desenvolvimento web. Conheça um pouco do meu trabalho.

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>