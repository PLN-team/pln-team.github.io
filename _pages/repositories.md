---
layout: page
permalink: /repositories/
title: repositories
description: public repositories from our github organisation
giscus_comments: true
nav: true
nav_order: 2
---

People who contributed to the code of `PLNmodels` (by order of importance)

<a href="https://github.com/pln-team/PLNmodels/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=pln-team/PLNmodels" />
</a>

## GitHub Repositories

{% if site.data.repositories.github_repos %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.html repository=repo %}
  {% endfor %}
</div>
{% endif %}
