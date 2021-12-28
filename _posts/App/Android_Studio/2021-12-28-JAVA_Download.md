---
title:  "[안드로이드스튜디오] Window 10 JAVA 설치하기"
excerpt: "Window10 JAVA Installation"

categories:
  - Android_Studio
tags:
  - [JAVA]

toc: true
toc_sticky: true
 
date: 2021-12-28
last_modified_at: 2021-12-28
---

# JAVA 설치하기


---

# 1. 오라클 사이트에 접속해서 파일 다운로드한다

[https://www.oracle.com/java/technologies/downloads/#java11](https://www.oracle.com/java/technologies/downloads/#java11)를 접속해서 다운로드를 해주세요.  
  
  ![스크린샷(26)](https://user-images.githubusercontent.com/55564114/147544904-cceecb5c-b3da-4d30-826c-43e285509dd4.png)  


---

# 2. 다운로드 한 파일을 실행하고 설치한다

![스크린샷(27)](https://user-images.githubusercontent.com/55564114/147545093-2dd778be-8b68-480b-acb5-179da56b252d.png)  
  
  ![스크린샷(28)](https://user-images.githubusercontent.com/55564114/147545207-ecc63907-af6c-4a34-ad90-2ab6d609361e.png)  
    
  ![스크린샷(29)](https://user-images.githubusercontent.com/55564114/147545321-07fab6d7-d4b4-49cf-9f63-00a4a9aeb24e.png)  

    설치가 완료되었습니다.  

---

# 3. 환경변수 설정하기

![스크린샷(30)](https://user-images.githubusercontent.com/55564114/147545584-fc914c2e-e156-44ac-ac46-85e15b39e527.png)  
  
    ○ 내 PC 에 마우스 오른쪽 클릭 -> 속성(R) 클릭  

![스크린샷(31)](https://user-images.githubusercontent.com/55564114/147546343-0dec875f-f863-44eb-a254-bf34030eda47.png)  
  
    ○ 우측에 고급 시스템 설정 클릭  

![스크린샷(32)](https://user-images.githubusercontent.com/55564114/147546509-808c6e94-2dc4-4e6c-ad31-3639c33f35f1.png)  

    ○ 환경 변수(N) 클릭  

![스크린샷(33)](https://user-images.githubusercontent.com/55564114/147547384-9680f371-3878-4525-8c2f-4a0ac2b32e80.png)  

    ○ 새로 만들기(W) 클릭  

![스크린샷(34)](https://user-images.githubusercontent.com/55564114/147547560-5478f6f1-f361-496b-8b95-3283dfca4321.png)  

    ○ 위와 같은 사진처럼 Java 폴더 안에 bin 폴더 까지 경로를 복사해줍니다  

![스크린샷(35)](https://user-images.githubusercontent.com/55564114/147548158-09b9fdd1-106b-4155-bb5a-49dced197089.png)  

    ○ 변수 이름(N) : JAVA_HOME 
    ○ 변수 값(V) : C:\Program Files\Java\jdk-17.0.1\bin 
    ○ 확인 클릭  

![스크린샷(36)](https://user-images.githubusercontent.com/55564114/147548530-20e2eac7-e205-4924-8fca-72dcbc135a5b.png)  

    ○ 시스템 변수(S) 에서 Path 를 선택 후, 편집(I) 클릭  

![스크린샷(38)](https://user-images.githubusercontent.com/55564114/147549121-3d360b3f-384c-4a3b-824a-9e5ec985a3ac.png)  
 
    ○ 새로 만들기(N) 클릭  
    ○ %JAVA_HOME% 입력  
    ○ 확인 클릭  

---

# 4. 설치 확인하기

![스크린샷(40)](https://user-images.githubusercontent.com/55564114/147549416-7c80eea1-8626-4da4-bea3-5ef6876adf6d.png)  

    ○ CMD 실행  
    ○ javac 입력
    ○ 위 사진처럼 뜨면 설치가 완료!  

---

# 여담

간만에 JAVA를 설치해보니까 예전보다 편해진거 같네요 ㅎ  


---












