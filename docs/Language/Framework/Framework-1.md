---
title: 2024-04-11 Django Nomal Set
layout: default
parent: Framework
grand_parent: Language
published_date: 2024-04-11
last_modified_date: 2024-04-11
permalink: 'django-1'
---
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}
---
## Django 기본 구축하기
<br>

#### 0. Django 소개
Python에서 제일 많이 알려진 웹프레임워크이며, 2005년 공개 후 오픈소스가 가장 많다.<br>
웹 개발에 필요한 거의 모든것을 포함되어있고, 기본디자인이나 인터페이스를 구현하기 쉽다.
1. 모델, 템플릿, 뷰 구성요소를 통해 애플리케이션을 구성한다. (MTV)
2. 개발자가 SQL 데이터베이스를 직접 세팅하지 않아도 기본 데이터베이스를 구성할 수 있다.
3. 웹 보안 문제로부터 보호하는 기능을 내장하고 있다.

#### 1. Python 패키지 설치
```python
python venv [folder] # 가상환경 세팅

pip install django, mysqlclient # 패키지 설치

django-admin startproject [프로젝트 이름] # django 프로젝트 폴더 만들기
```

#### 2. mysite/setting.py의 데이터베이스구성 수정

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

#### 3. 서버 실행하기
```python 
python manage.py runserver
```

#### 4. 마이그레이션
```python
python manage.py migrate
```
