---
title: 2024-05-18 Django Requests
layout: default
parent: Framework
nav_order : 7.1
grand_parent: Language
published_date: 2024-05-18
last_modified_date: 2024-05-23
permalink: 'django-2'
keywords: ["django","API"]
published : true
---
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}
---
## Django 기본 API
<br>

### 0. 소개
이전 Django 데이터에서 진행했던 기본API 세팅의 Requests 의 코드를 작성하는 글<br>

`import requests`

### 1. 데이터 추가
```python
url = 'http://localhost:8000/api/board/'
data = {
    'name': 'New Post',
    'description': 'This is the content of the new post.'
}

response = requests.post(url, data=data)

if response.status_code == 201:
    print('New post created:', response.json())
else:
    print('Failed to create new post:', response.status_code)
```

### 2. 데이터 조희
1. 전체 데이터 조회
```python
url = f'http://localhost:8000/api/board/'

response = requests.get(url)

if response.status_code == 200:
    print('Board Detail:', response.json())
else:
    print('Failed to retrieve board detail:', response.status_code)
```
2. 선택 데이터 조회
```python
post_id = 1  # 조회할 데이터의 ID
url = f'http://localhost:8000/api/board/{post_id}/'

response = requests.get(url)

if response.status_code == 200:
    print('Board Detail:', response.json())
else:
    print('Failed to retrieve board detail:', response.status_code)
```

### 3. 데이터 수정
```python
post_id = 1  # 수정할 데이터의 ID
url = f'http://localhost:8000/api/board/{post_id}/'
data = {
    'title': 'Updated Post',
    'content': 'This is the updated content of the post.'
}

response = requests.put(url, data=data)

if response.status_code == 200:
    print('Post updated:', response.json())
else:
    print('Failed to update post:', response.status_code)
```

### 4. 데이터 삭제
```python
post_id = 1  # 삭제할 데이터의 ID
url = f'http://localhost:8000/api/board/{post_id}/'

response = requests.delete(url)

if response.status_code == 204:
    print('Post deleted successfully')
else:
    print('Failed to delete post:', response.status_code)
```