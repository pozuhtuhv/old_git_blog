---
title: 환경변수 .env
layout: default
parent: Python
nav_order : 4.11
grand_parent: Language
published_date: 2024-10-12
last_modified_date: 2024-10-12
permalink: 'python-2'
keywords: ["module"]
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

## 환경변수 .env

`.env 파일 환경변수`<br>


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
토큰 데이터나 고정해놔야할 값이 있으면 따로 작성해서 혼란없게 따로 빼놓는 방법
```
