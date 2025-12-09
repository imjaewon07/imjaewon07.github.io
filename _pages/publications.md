---
layout: page
permalink: /publications/
title: publications
description:
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

<div class="publications" markdown="1">

### Methodological Research

{% bibliography --query @*[keywords~=methodology] %}

### Applied Research

{% bibliography --query @*[keywords~=applied] %}

</div>
