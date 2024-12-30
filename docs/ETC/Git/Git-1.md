---
title: 20240522 깃오류.
layout: default
grand_parent: ETC
parent: Git
permalink: '{{ page.parent | downcase }}/{{ page.url | replace: ".md", "" | downcase }}'
nav_order : 11.1
published_date: 2024-05-22
last_modified_date: 2024-05-22
keywords: ["error"]
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

## Git Error

### 1. fatal: protocol 'https' is not supported
<br>
git bash 를 이용하다보면 나오는 그것<br>
'프로토콜 지원을 안함'<br>

눈으로 보기에는 'https' 만 보이겠지만<br>
bash 창에서는 'https' 앞에 문자는 표시 되지 않았던 것<br>

단순한 방법으로는 메모장에 붙여넣기하고 그걸 다시 복사<br>
이어서 명령어 진행하면 정상적이게 진행된다.<br>

### 2. Git Bash의 복사, 붙여넣기단축키
<br>
- 복사하기 (Copy) : <br>
Ctrl + Insert

- 붙여넣기 (Paste) : <br>
Shift + Insert