---
title:  "[안드로이드스튜디오] Android sdkmanager not found. Update to the latest Android SDK and ensure that the cmdline-tools are installed to resolve this. 해결방법 "
excerpt: "Android sdkmanager not found. Update to the latest Android SDK and ensure that the cmdline-tools are installed to resolve this. 해결방법"

categories:
  - Android_Studio
tags:
  - [Error]

toc: true
toc_sticky: true
 
date: 2021-12-30
last_modified_at: 2021-12-30
---

# Android sdkmanager not found. Update to the latest Android SDK and ensure that the cmdline-tools are installed to resolve this.

---

# 1. 문제 

![스크린샷(73)](https://user-images.githubusercontent.com/55564114/147737283-57a31c9b-7d90-42d8-b240-ff6981157768.png)  

        Problem : Android sdkmanager not found. Update to the latest Android SDK and ensure that the cmdline-tools are installed to resolve this.
          
        번역 : Android SDK 관리자를 찾을 수 없습니다. 최신 Android SDK로 업데이트하고 cmdline-tools가 설치되어 이 문제를 해결하는지 확인하십시오.

---

# 2. 해결 방법

![스크린샷(74)](https://user-images.githubusercontent.com/55564114/147737620-953a46e0-7aec-4559-9776-3027f97d4c6b.png)  

    ○ Tools - SDK Manager 클릭

![스크린샷(75)](https://user-images.githubusercontent.com/55564114/147737932-b2a24cdf-6912-4bd9-9a73-5a10fef5153a.png)  

    ○ SDK Tools 클릭 - Hide Obsolete Packages 체크 해제 
    ○ Android SDK Tools (Obsolete) 설치 (※참고 : 저는 이미 설치되어있는데 동일한 에러가 발생)
    ○ Android SDK Command-line Tools (latest) 설치 

![스크린샷(77)](https://user-images.githubusercontent.com/55564114/147738317-bea0d6bb-6d4e-4f6c-afa6-1212c13d6b14.png)  

    ○ 설치 후 다시 입력해주세요 
    ○ 해결은 되었지만 새로운 문제를 해결해야 될거같네요...
    ○ ERROR: JAVA_HOME is set to an invalid directory: C:\Program Files\Java\jdk-17.0.1\bin
    ○ Please set the JAVA_HOME variable in your environment to match the location of your Java installation.

---

# ERROR: JAVA_HOME is set to an invalid directory: C:\Program Files\Java\jdk-17.0.1\bin

Please set the JAVA_HOME variable in your environment to match the location of your Java installation.

    ○ 제 블로그를 포스팅을 확인해주세요


---





