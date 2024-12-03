---
title: 20240822 워크플로우 권한.
layout: default
parent: Git
grand_parent: ETC
published_date: 024-08-22
last_modified_date: 024-08-22
permalink: 'git-2'
keywords: ["permission"]
published : true
---
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}
---

## github actions workflow permission

### 쓰기 권한 설정 하기
<br>

1. Settings 페이지

    ![docs](/img/git-2.1.png)<br>

2. Actions 탭 -> General 메뉴

    ![docs](/img/git-2.2.png)<br>

3. Workflow Permissions

    ![docs](/img/git-2.3.png)<br>

    Read and write permissions: 워크플로우가 레포지토리의 모든 범위에서 읽기 및 쓰기 권한을 가지도록 설정.<br>
    
    Read repository contents and packages permissions: 워크플로우가 레포지토리의 콘텐츠 및 패키지 범위에 대해서만 읽기 권한을 가지도록 설정.