---
layout: page
title: 搜索本站
date: 
modified:
excerpt:
image:
  feature:
search_omit: true
sitemap: false
---
  
<!-- Search form -->
<form method="get" action="{{ site.url }}/search/" data-search-form class="simple-search">
  <label for="q">Search {{ site.title }} for:</label>
  <input type="search" name="q" id="q" placeholder="填入你搜索的内容" data-search-input id="goog-wm-qt" autofocus />
  <input type="submit" value="搜索" id="goog-wm-sb" />
</form>

<!-- Search results placeholder -->
<h6 data-search-found>
   &ldquo;<span data-search-found-term></span>&rdquo;有<span data-search-found-count></span> 条搜索结果.
</h6>
<ul class="post-list" data-search-results></ul>

<!-- Search result template -->
<script type="text/x-template" id="search-result">
  <li><article>
    <a href="##Url##">##Title## <span class="excerpt">##Excerpt##</span></a>
  </article></li>
</script>
