---
layout: page
permalink: /repositories/
title: repositories
description:
nav: true
nav_order: 3
---

## GitHub users

{% if site.data.repositories.github_users %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for user in site.data.repositories.github_users %}
    {% include repository/repo_user.html username=user %}
  {% endfor %}

{% endif %}

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
github repository:
</div>

[softlab-unimore](https://github.com/softlab-unimore).
---


