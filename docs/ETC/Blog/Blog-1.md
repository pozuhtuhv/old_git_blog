---
title: 20240410 JTD Font Set.
layout: default
grand_parent: ETC
parent: Blog
permalink: 'etc/blog/blog-1'
nav_order : 9
published_date: 2024-04-10
last_modified_date: 2024-04-10
keywords: ["gitblog","gitblogfont"]
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

## Noto Sans KR 폰트 적용
<br>

### 1. head.html 추가

path : _includes/head.html<br>
line : 16 ~
```html
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=Edge">
  <link href="https://fonts.googleapis.com/..." rel="stylesheet"> <!-- 폰트 스타일시트 -->
```

<br>

### 2. custom.scss 추가

path : _sass/custom/custom.scss<br>
line : 0 ~
```scss
p, a, h1, h2, h3, h4, h5, h6 {
    font-family: "Noto Sans KR";
}
```

`테마 별로 다른 방법이 있다고 하는데 이 방법이 제일 편한거 같아서 강제적용`