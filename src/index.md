---
title: 'Bups World'
layout: 'layouts/feed.njk'
metaDesc: '11ty theme'
imageURL: /images/background.jpg
pagination: 
  data: collections.blog
  size: 7
permalink: '{% if pagination.pageNumber > 0 %}/page/{{ pagination.pageNumber }}{% endif %}/index.html'
paginationPrevText: 'Newer posts'
paginationNextText: 'Older posts'
paginationAnchor: '#post-list'
eleventyNavigation:
  key: Home
  title: 🏠 Home
  order: 1
---
Reisen mit dem Bups. Wir lassen uns überraschen. 