---
title: 2024-05-08 Git repo upload.
layout: default
parent: Blog
grand_parent: ETC
published_date: 2024-05-08
last_modified_date: 2024-05-08
permalink: 'blog-2'
---
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}
---
## Git Bash -> Repo upload
<br>

#### 1. Git Bash로 업로드할 폴더 설정

폴더에서 마우스 우측 -> Open Git Bash here<br>

#### 2. Git Bash 명령어 하나씩 수행
```bash
git init
git branch -m main
git remote add origin "ropo.git.url"
git add .
git commit -m "commit 내용"
git push -u origin main
```

`다른 오류 없이 편하게 업로드 가능`