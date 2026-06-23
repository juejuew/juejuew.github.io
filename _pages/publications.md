---
layout: page
permalink: /publications/
title: Research
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<div class="publications">

<h2>Papers</h2>

{% bibliography --group_by none --query @unpublished %}

<h2>Theses</h2>

{% bibliography --group_by none --query @misc %}

</div>
