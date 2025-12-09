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

<div class="publications">

### Methodology

{% bibliography --query @*[keywords~=methodology] %}

### Applied

{% bibliography --query @*[keywords~=applied] %}

</div>
