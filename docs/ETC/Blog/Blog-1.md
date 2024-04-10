---
title: 2024-04-10 JTD Font Set.
layout: default
parent: Blog
grand_parent: ETC
published_date: 2024-04-10
last_modified_date: 2024-04-10
permalink: 'blog-1'
---

## Noto Sans KR 폰트 적용
<br>
###1. head.html 추가
<br>
'_includes/head.html' 경로에 16line ~ head 직접 추가
<br>
```html
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=Edge">
  <link href="https://fonts.googleapis.com/..." rel="stylesheet">
```
<br>
###2. base.scss 수정
<br>
'_sass/base.scss' 경로에 18line ~ 직접 수정 
<br>
```html
  body {
    font-family: 'Noto Sans KR'; <!-- 폰트이름으로 변경 -->
    font-size: inherit;
    line-height: $body-line-height;
    color: $body-text-color;
    background-color: $body-background-color;
    overflow-wrap: break-word;
  }
```

## 테마 별로 다른 방법이 있다고 하는데 이 방법이 제일 최고인거 같아서 강제적용