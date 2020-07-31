---
layout: page
title: Search
---

<!-- Html Elements for Search -->
<div class="entry">
<div id="search-container">
    <input type="text" id="search-input" placeholder="Search through blog posts...">
    <ul id="results-container"></ul>
</div>
</div>

<!-- Configuration -->
<script>
SimpleJekyllSearch({
      searchInput: document.getElementById('search-input'),
      resultsContainer: document.getElementById('results-container'),
      json: '/search.json',
      searchResultTemplate: '<h1><a class="site-name" href="{{ site.url }}{url}">{title}</a></h1>'
})
</script>
