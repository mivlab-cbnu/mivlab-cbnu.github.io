---
title: Publications
nav:
  order: 3
  # tooltip: Published works
---

# {% include icon.html icon="fa-solid fa-microscope" %}Publications

{% include button.html icon="fa-brands fa-google" text="More on Google Scholar" link="https://scholar.google.com/citations?hl=en&user=BEhSvN4AAAAJ&view_op=list_works&authuser=1&sortby=pubdate" %}



<!-- ## All publications -->

<div class="button-row">
  {% include button.html text="All" link="/publications/?search=" style="bare" %}
  {% include button.html text="International journal" link="/publications/?search=%22tag:%20international-journal%22" style="bare" %}
  {% include button.html text="International conference" link="/publications/?search=%22tag:%20international-conference%22" style="bare" %}
  {% include button.html text="Domestic paper" link="/publications/?search=%22tag:%20domestic-paper%22" style="bare" %}
  {% include button.html text="Patent" link="/publications/?search=%22tag:%20patents%22" style="bare" %}
</div>

{% include search-box.html disabled=false %}

{% include search-info.html %}

{% include section.html %}

{% include list.html data="citations" component="citation" style="rich" %}

