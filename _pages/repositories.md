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


## github repository:
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
[softlab-unimore](https://github.com/softlab-unimore)
</div>



## youtube account:

[softlab-unimore](https://www.youtube.com/@softlab-unimore2549/featured)


---


