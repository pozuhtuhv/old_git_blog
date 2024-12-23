---
title: 20241223 JTD Sitemap.
layout: default
grand_parent: ETC
parent: Blog
permalink: 'blog-2'
nav_order : 9.11
published_date: 2024-12-23
last_modified_date: 2024-12-23
keywords: ["sitemap"]
published : true
---
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}
---

<!-- 글의 제목은 ##
    나머지 큰 제목은 ###
    이후 나머지는 4개이상 -->

## Just The Docs 사이트맵 설정

### 1. _config.yml plugins 추가

_config.yml 파일의 plugins: 부분에 '  - jekyll-sitemap' 추가

```yml
~
plugins:
  - jekyll-seo-tag
  - jekyll-github-metadata
  - jekyll-include-cache
  - jekyll-sitemap
~
```
