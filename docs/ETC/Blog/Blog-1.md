---
title: 2024-04-10 JTD Font Set.
layout: default
parent: Blog
grand_parent: ETC
published_date: 2024-04-10
last_modified_date: 2024-04-10
permalink: 'blog-1'
---
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}
---
## Noto Sans KR 폰트 적용
<br>

#### 1. head.html 추가

path : _includes/head.html<br>
line : 16 ~
```html
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=Edge">
  <link href="https://fonts.googleapis.com/..." rel="stylesheet">
```

<br>

#### 2. custom.scss 추가

path : _sass/custom/custom.scss<br>
line : 0 ~
```scss
p, a, h1, h2, h3, h4, h5, h6 {
    font-family: "Noto Sans KR";
}
```

`테마 별로 다른 방법이 있다고 하는데 이 방법이 제일 편한거 같아서 강제적용`