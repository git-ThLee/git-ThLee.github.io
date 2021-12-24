---
title:  "[블로그] Git에서 user name 및 user email 을 구성 하세요"
excerpt: "Git에서 user name 및 user email 을 구성 하세요"

categories:
  - Blog_dev
tags:
  - [Blog , VS , VSC]

toc: true
toc_sticky: true
 
date: 2021-12-24
last_modified_at: 2021-12-24
---

# 1. 문제 : Git에서 user name 및 user email 을 구성 하세요

카페에서 노트북으로 블로그를 수정할랬더니 뜨더라구요ㅎㅎ  
참고로 노트북으로는 Code부터 Git까지 처음부터 설치를 했거든요.  
  
설치를 하다고 업로드 할려니까  
**Git에서 user name 및 user email 을 구성 하세요** 발생하더라구여.

---

# 2. 해결방법

제가 해결한 방법대로 알려드릴게요.  

## 2.1 ) Git Bash 를 켠다

작업표시줄에서 "Git" 만 처도 나올거에요.  
안나오면 Git 부터 다시 설치해주세요.  

## 2.2 ) $ git config --global user.name "Your Name" 입력

ex) $ git config --global user.name "Hoon.git"  

## 2.3 ) $ git config --global user.email you@example.com 입력

ex) $ git config --global user.email you@naver.com 
  
  2가지를 입력하면 ~/.gitconfig 에 내용이 추가되요.  

  ```
  $ cat ~/.gitconfig
    [user]
    name = Hoon.git
    email = you@naver.com
  ```

## 2.4 ) Code를 재실행하고 업로드를 실행한다

저는 위와 같이 하니까 해결되더라구여 ㅎㅎ  

---

끝

---


