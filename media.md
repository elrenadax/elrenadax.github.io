---
layout: page
title: Media
permalink: /media/
hide_title: true
---

<div class="tabs" role="tablist">
  <button class="tab active" type="button" data-tab="books" role="tab" aria-selected="true">books</button>
  <button class="tab" type="button" data-tab="blogs" role="tab" aria-selected="false">blogs</button>
  <button class="tab" type="button" data-tab="podcasts" role="tab" aria-selected="false">podcasts</button>
  <button class="tab" type="button" data-tab="music" role="tab" aria-selected="false">music</button>
  <button class="tab" type="button" data-tab="movies" role="tab" aria-selected="false">movies</button>
</div>

{% include panel-books.html %}
{% include panel-blogs.html %}
{% include panel-podcasts.html %}
{% include panel-music.html %}
{% include panel-movies.html %}

<script>
{% include tabs-state.js %}
</script>
