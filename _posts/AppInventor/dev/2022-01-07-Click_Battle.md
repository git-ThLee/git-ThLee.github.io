---
title:  "[앱인벤터] 클릭 배틀 게임"
excerpt: "클릭 배틀 게임"

categories:
  - AppInventor_dev
tags:
  - [Click]

toc: true
toc_sticky: true
 
date: 2022-01-07
last_modified_at: 2022-01-07
---

# 클릭 배틀 게임 만들기

---  

![Animation](https://user-images.githubusercontent.com/55564114/148487058-b86b0e11-7868-4cc9-94bd-fc4bc5f910c4.gif)  

- 작동 원리
  1. 버튼(시작)을 클릭한다
  2. 1 ~ 3 초 사이 랜덤하게 준비시간을 준다
  3. 5초 동안 버튼(빨강), 버튼(파랑) 각각 클릭한다
  4. 클릭 수가 더 많은 팀이 승리한다

😉😉🥰🥰

---

## 1. 디자인

![스크린샷(106)](https://user-images.githubusercontent.com/55564114/148488153-3c27ebe9-1ce7-4841-ab7a-60d1e6b52da6.png)  

---

### #디자인 구조

| 1 | 2 | 3 | 4 | 
| :---: | :---: | :---: | :---: | 
| Screen1 |  |  |
|└|버튼_빨강팀|
|└|수평배치||
||└|버튼_시작|
||└|레이블_타이머|
|└|버튼_파랑팀|
|보이지 않는|
|1|시계_타이머|
|2|시계_시작|
|3|알림|


**구체적인 속성이 궁금하시면 댓글 적어주세요**

---

## 2. 만들어야할 기능 

1. 버튼(시작)을 클릭하면, 시계(시계_시작)을 작동시키고, "랜덤하게 시작됩니다" 알림 띄우기

2. "랜덤하게 시작됩니다" 알림이 1 ~ 3초 후에 사라지면, 시계(시계_타이머) 작동시키고, 카운트 시작하기

3. 카운트 중에 버튼(빨강), 버튼(파랑) 각각 클릭하기

4. 카운트가 끝나면 클릭수를 비교해서 승리팀 알림 띄우기

---

## 3. 블록코딩

### #한글버전
![스크린샷(107)](https://user-images.githubusercontent.com/55564114/148489199-5150ee70-fdc8-491e-ab69-12d9ea65c783.png)  

![스크린샷(108)](https://user-images.githubusercontent.com/55564114/148489305-8b5a7a3e-6e6c-4140-89ae-b0d46ee0aeb9.png)  

![스크린샷(109)](https://user-images.githubusercontent.com/55564114/148489381-a22e73d8-fec8-4849-b9a9-e8ecc23c8e9a.png)  


### #영어버전
![스크린샷(111)](https://user-images.githubusercontent.com/55564114/148489423-7fb01b64-a3c2-4be2-9255-2359ab82d202.png)  

![스크린샷(112)](https://user-images.githubusercontent.com/55564114/148489588-f1c772c0-44ab-4b01-a1a5-25d9d969af11.png)  

![스크린샷(110)](https://user-images.githubusercontent.com/55564114/148489621-08978bd1-f4f9-481c-a43a-2e018c183297.png)  


---

추가적으로 버튼(빨강)은 클릭해줄 때마다 색상 바뀌게 해봤습니다.  


궁금하신 부분은 댓글주시거나 메일 주시면 됩니다.🥰🥰  

---

