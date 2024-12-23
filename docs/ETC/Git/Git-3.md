---
title: 20240508 Git repo upload.
layout: default
grand_parent: ETC
parent: Git
permalink: 'git-3'
nav_order : 11.111
published_date: 2024-05-08
last_modified_date: 2024-12-23
keywords: ["gitupload"]
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

## Git Bash -> Repo upload
<br>

### 1. Github에 NEW 리포지토리 git repo url 확인
<br>

![docs](/assets/images/blog-2.1.png)<br>
git repo url copy<br>

### 2. Git Bash로 업로드할 폴더 설정
<br>

폴더에서 마우스 우측 -> 'Open Git Bash here'<br>

### 3. Git Bash 명령어 하나씩 수행
<br>

```bash
git init
git branch -m main
git remote add origin "git ropo url"
git add .
git commit -m "commit 내용"
git push -u origin main
```

`다른 오류 없이 편하게 업로드 가능`
