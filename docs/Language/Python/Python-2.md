---
title: python .env
layout: default
parent: Python
nav_order : 4.11
grand_parent: Language
published_date: 2024-04-11
last_modified_date: 2024-04-11
permalink: 'python-1'
keywords: ["codereview"]
published : true
---
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}
---
## Python .env 파일 환경변수
<br>

`Python .env 파일 환경변수`<br>


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

user = os.getenv('ABC')
```

<br>

#### 꽤나 자주쓰일만한 자료

```html
토큰 데이터나 고정해놔야할 값이 있으면 따로 작성해서 혼란없게 따로 빼놓는 방법
```