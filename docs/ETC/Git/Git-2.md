---
title: 20240822 워크플로우 권한.
layout: default
grand_parent: ETC
parent: Git
permalink: 'etc/git/git-2'
nav_order : 11.11
published_date: 2024-08-22
last_modified_date: 2024-08-22
keywords: ["permission"]
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

## Github Actions Workflow Permission

### 1. 권한 설정 하기
<br>

1. Settings 페이지

![docs](/assets/images/git-2.1.png)<br>

1. Actions 탭 -> General 메뉴

![docs](/assets/images/git-2.2.png)<br>

1. Workflow Permissions

![docs](/assets/images/git-2.3.png)<br>

Read and write permissions: 워크플로우가 레포지토리의 모든 범위에서 읽기 및 쓰기 권한을 가지도록 설정.<br>

Read repository contents and packages permissions: 워크플로우가 레포지토리의 콘텐츠 및 패키지 범위에 대해서만 읽기 권한을 가지도록 설정.