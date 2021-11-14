---
title:  "[블로그] 깃허브 와 비쥬얼스튜디오 연동하기"
excerpt: "깃허브 블로그를 비쥬얼스튜디오에서 사용하기"

categories:
  - Blog
tags:
  - [Blog , VS , VSC]

toc: true
toc_sticky: true
 
date: 2021-11-14
last_modified_at: 2021-11-14
---

# 0. 비쥬얼스튜디오에서 깃허브 블로그 연동해보기

  많은 분들이 깃허브 블로그를 사용해서 포스팅을 하고 있죠.  
  하지만 모든 사람이 같은 프로그램을 이용하진 않을 거에요.  
  저는 **Visual Studio**을 사용중이며,  
    
    깃허브와 연동을 해볼게요. 

# 1. VSCODE에서 F1키를 누르고, "git clone" 입력하기

  비쥬얼스튜디오를 키시고, F1키를 눌러보세요.  
  그럼 상단에 입력할 수 있는 곳이 생겨요.  
  "git clone"을 입력하기.
    
    만약 1 ) "No matching commands" 뜬다면 ? 
      [여기](https://git-scm.com/) 을 클릭해서 깃허브를 설치해주세요.  
      아니면 따로 깃허브를 구글에 검색해서 설치해주셔도 되요.
    
    만약 2 ) "리포지토리 URL을 입력하거나 리포지토리 소스를 선택하세요" 뜬다면?  
      전 포스팅에서 Fork했던 리포지토리에 가서 아래 그림과 같이 클릭을 해주시고,  
      아래 그림에 "리포지토리 URL을 입력하거나 리포지토리 소스를 선택하세요"에 입력해주세요.  

  ![스크린샷(55)](https://user-images.githubusercontent.com/55564114/141675005-2ef840be-780d-48a6-aed8-7b19e94a441f.png)  

  ![스크린샷(55) (1)](https://user-images.githubusercontent.com/55564114/141675062-09ba873d-5003-4f3e-805f-372460f79308.png)  

---

# 2. URL 입력 하시고, 로컬 PC에 저장할 위치 선택하기

원하시는 위치를 지정해주시면 되요.  

---

# 3. 비쥬얼 스튜디오에서 로컬 PC에 저장한 폴더 열기

저장을 하시고나면 우측 하단에 **"Would you like to open the cloned repository?"** 라고 뜬다면 아래 둘중 하나 눌러주세요.  

- Open : 현재 창에서 열기  
- Open in New Window : 새창에서 열기  

---

# 4. 테스트 : _config.yml에서 title 변경해보기.

1. _config.yml 열기 (최상위 폴더)
2. title : 에서 "" 안에 수정하기. 
3. 폴더 안에 무언가 변경이 발생하면 좌측 3번째 아이콘에 숫자가 생겨요
4. 아래 그림 처럼 따라 클릭
5. "모두 저장 및 커밋" or "스테이징된 변경 사항 커밋" 클릭
6. 커밋메시지 작성
7. 변경 내용 동기화 클릭 (이거 안하면 블로그 안바뀜)
8. 블로그 들어가서 변경사항 확인(길게는 몇분이 걸릴수도 있어요.)

![스크린샷(58)](https://user-images.githubusercontent.com/55564114/141675808-a8c83dbd-9b8b-439c-aac6-f33c9da4c88a.png)  

![스크린샷(59)](https://user-images.githubusercontent.com/55564114/141675841-7f5fb0fb-f969-441a-b852-d9d7454d1fe2.png)  

![스크린샷(60)](https://user-images.githubusercontent.com/55564114/141675892-f09be889-6e01-4584-b8ec-28a3b83c4418.png)  

![스크린샷(61)](https://user-images.githubusercontent.com/55564114/141675926-c05fbdb5-8a85-4ae9-b5d3-b7faee7c8c75.png)  

![스크린샷(63)](https://user-images.githubusercontent.com/55564114/141676166-36de115a-022e-40db-84c6-086f0056524e.png)  

---

### * 커밋이란 

![스크린샷(62)](https://user-images.githubusercontent.com/55564114/141676087-adda0eb7-7798-4edb-b0de-9f98cb00ab0b.png)  

**깃허브에서 박스가 있는 부분에 여러분이 쓴 커밋메시지가 들어가게 되요.**

---





---






