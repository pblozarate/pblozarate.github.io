---
layout: page
permalink: /publications/
title: Research
description:
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h2 class="bibliography" style="text-align: left; color: var(--global-text-color);">Job Market Paper</h2>
{% bibliography --group_by none --query @*[category=jmp]* %}

<h2 class="bibliography" style="text-align: left; color: var(--global-text-color);">Working Papers</h2>
{% bibliography --group_by none --query @*[category=working]* %}

<h2 class="bibliography" style="text-align: left; color: var(--global-text-color);">Work in Progress</h2>
{% bibliography --group_by none --query @*[category=progress]* %}

</div>
