---
layout: page
permalink: /publications/
title: Publications
description: 
nav: true
nav_order: 2
---
<style>
  .publications .abbr {
    display: none;
  }

  @media (min-width: 576px) {
    .publications .row > .col-sm-8 {
      flex: 0 0 83.333333%;
      max-width: 83.333333%;
    }
  }
</style>

<!-- _pages/publications.md -->

Also see my [Google Scholar profile](https://scholar.google.com/citations?hl=en&user=3K-dyUkAAAAJ&view_op=list_works).

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography %}

</div>
