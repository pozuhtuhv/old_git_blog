---
title: 20241012 변수.env
layout: default
grand_parent: Framework
parent: FPython
permalink: 'framework/fpython/fpython-5'
nav_order: 7.11111
published_date: 2024-10-12
last_modified_date: 2024-10-12
keywords: ["module"]
published: true
---
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}
---

<!-- 글의 제목은 ##
    나머지 큰 제목은 ###
    이후 나머지는 4개이상 -->

## 변수 .env

`.env 파일 변수`<br>


### 모듈 설치
```python
pip install python-dotenv
```

### .env 파일 내용
```python
USER = 'ABC'
```

### 실행 예시
```python
import os
from dotenv import load_dotenv

load_dotenv()

user = os.getenv('USER')
```

<br>

### 부가설명

```html
토큰 데이터나 고정값을 변수로 적용해놓는 방법
```
