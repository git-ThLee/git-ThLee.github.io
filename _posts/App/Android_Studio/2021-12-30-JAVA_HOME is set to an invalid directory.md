---
title:  "[안드로이드스튜디오] ERROR: JAVA_HOME is set to an invalid directory: C:\Program Files\Java\jdk-17.0.1\bin Please set the JAVA_HOME variable in your environment to match the location of your Java installation. 해결방법 "
excerpt: "ERROR: JAVA_HOME is set to an invalid directory: C:\Program Files\Java\jdk-17.0.1\bin Please set the JAVA_HOME variable in your environment to match the location of your Java installation. 해결방법"

categories:
  - Android_Studio
tags:
  - [Error]

toc: true
toc_sticky: true
 
date: 2021-12-30
last_modified_at: 2021-12-30
---

# ERROR: JAVA_HOME is set to an invalid directory: C:\Program Files\Java\jdk-17.0.1\bin Please set the JAVA_HOME variable in your environment to match the location of your Java installation.

---

# 1. 문제 

![스크린샷(77) (1)](https://user-images.githubusercontent.com/55564114/147738911-7220297d-e152-4c7e-b4e8-5d7964fc8b14.png)

---

# 2. 해결 방법 1

![스크린샷(78)](https://user-images.githubusercontent.com/55564114/147739181-84860633-fbab-4338-8920-d39461ea22e0.png)  

    ○ 내 PC 마우스 우측 클릭 - 속성 클릭

![스크린샷(79)](https://user-images.githubusercontent.com/55564114/147739252-c87d37db-88fa-4f08-b60a-21bd296ba0bb.png)  

    ○ 고급 시스템 설정 클릭

![스크린샷(80)](https://user-images.githubusercontent.com/55564114/147739320-6656216e-42e5-4f26-89cd-dd06691cfeab.png)  

    ○ 환경 변수 클릭

![스크린샷(81)](https://user-images.githubusercontent.com/55564114/147739456-5395d501-7816-44be-b895-bb8eb3e06471.png)  

    ○ JAVA_HOME 선택 - 편집 클릭 

![스크린샷(83)](https://user-images.githubusercontent.com/55564114/147739537-94dedef7-da6d-4928-adc5-047d8c1d0e60.png)  

    ○ 변수 값 변경해주기  
    ○ 변경 전 : C:\Program Files\Java\jdk-17.0.1\bin 
    ○ 변경 후 : C:\Program Files\Java\jdk-17.0.1

![스크린샷(84)](https://user-images.githubusercontent.com/55564114/147739726-5d8e16f1-0cba-4c10-8a0b-4ee28825a37f.png)  

    ○ CMD 파일 재실행 
    ○ flutter doctor --android-licenses 입력 
    ○ y/n : 전부 y 동의해주기

---

# 3. 해결 방법 2

[https://github.com/flutter/flutter/issues/51712](https://github.com/flutter/flutter/issues/51712)에서 새로운 해결 방법이 있어서 따라해보았다  
  
[https://dl.google.com/android/repository/sdk-tools-windows-4333796.zip](https://dl.google.com/android/repository/sdk-tools-windows-4333796.zip) 파일을 다운로드

    ○ 1) 위 파일을 다운로드 하고 압축 해제를 한다. (※참고 : tools 파일 들어있음)
    ○ 2) C:\Users%User%\AppData\Local\Android\Sdk 폴더 안에 tools 파일 붙여넣기


---

