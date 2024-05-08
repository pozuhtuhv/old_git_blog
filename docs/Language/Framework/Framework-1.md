---
title: 2024-04-11 Django Nomal Set
layout: default
parent: Framework
grand_parent: Language
published_date: 2024-04-11
last_modified_date: 2024-04-11
permalink: 'framework-1'
---
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}
---
## Django 기본 구축하기
<br>

#### 1. Python 패키지 설치
```python
python venv [folder] # 가상환경 세팅

pip install django, mysqlclient # 패키지 설치

django-admin startproject [프로젝트 이름] # django 프로젝트 폴더 만들기
```

#### 2. setting.py 기본구성 수정

```json
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'MYTEST',
        'USER': 'root',
        'PASSWORD': '1234',
        'HOST': 'localhost',
        'PORT': '3306',
    }
}
```

`이걸 설정하는 이유는 Django 기본 데이터베이스는 sqlite3 로 진행되기 때문에 mysql로 연결시켜주는 것`

#### 3. 서버 정상설치 확인하기
```python 
python manage.py runserver
```

#### 4. 마이그레이션
```python
python manage.py migrate
```
