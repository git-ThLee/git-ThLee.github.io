---
title:  "[앱인벤터] mbti 검색기"
excerpt: "mbti 검색기를 만들어보기"

categories:
  - AppInventor_dev
tags:
  - [MBTI]

toc: true
toc_sticky: true
 
date: 2022-01-07
last_modified_at: 2022-01-07
---

# mbti 검색기를 만들어보자

---  

![Animation](https://user-images.githubusercontent.com/55564114/148490475-11312855-660b-45e0-b1c6-5c5165362a2a.gif)  

- 작동 원리
  1. 스위치를 클릭해서 내 mbti를 만든다
  2. mbti에 맞는 성격유형을 검색한다

😉😉🥰🥰

---

## 1. 디자인

![스크린샷(113)](https://user-images.githubusercontent.com/55564114/148490700-7e37fab8-700e-43a1-89d4-9f84cdae9fac.png)  

---

### #디자인 구조

| 1 | 2 | 3 | 4 | 
| :---: | :---: | :---: | :---: | 
| Screen1 |  |  |
|└|수직배치|
||└|레이블_mbti|
||└|레이블_에너지방향|
||└|수평배치|
|||└|스위치_1번|
|||└|레이블_1번|
||└|레이블_인식방식|
||└|수평배치|
|||└|스위치_2번|
|||└|레이블_2번|
||└|레이블_결정방식|
||└|수평배치|
|||└|스위치_3번|
|||└|레이블_3번|
||└|레이블_삶의패턴|
||└|수평배치|
|||└|스위치_4번|
|||└|레이블_4번|
||└|레이블_결과|
|└|웹뷰어|
|보이지 않는||
|1|알림||


**구체적인 속성이 궁금하시면 댓글 적어주세요**

---

## 2. 만들어야할 기능 

1. 스위치(1~4번)을 클릭하면, 전역변수(MBTI)의 텍스트를 바꾸기

2. 전역변수(MBTI)에 맞는 성격유형을 전역변수(mbti_리스트)에서 찾기

3. 웹뷰어에서 전역변수(MBTI)에 맞는 사이트로 이동하기
> ex)
> 사이트 주소 
> [16Personalities](https://www.16personalities.com/ko/%EC%84%B1%EA%B2%A9%EC%9C%A0%ED%98%95-intj)  
> 주소의 "intj" 부분에 전역변수(MBTI)를 넣어주면 됨


---

## 3. 블록코딩

### #한글버전
![스크린샷(114)](https://user-images.githubusercontent.com/55564114/148491096-c25adf4c-d8ae-4fbe-8717-a948a75037c6.png)  

![스크린샷(115)](https://user-images.githubusercontent.com/55564114/148491181-da956d54-c173-42e8-8c1c-a789dd1763cf.png)  

![스크린샷(116)](https://user-images.githubusercontent.com/55564114/148491270-bee50a7f-b806-4e9b-96ee-0272a3fba754.png)
![스크린샷(117)](https://user-images.githubusercontent.com/55564114/148491314-3a360555-ab38-4383-9a1f-a1610b5af652.png)  

![스크린샷(118)](https://user-images.githubusercontent.com/55564114/148491372-bff4477a-2df1-415c-82dc-c29aa4ebbe20.png)  


### #영어버전
![스크린샷(119)](https://user-images.githubusercontent.com/55564114/148491483-f02665e5-3750-474f-a03e-e3b1ee24426d.png)  

![스크린샷(120)](https://user-images.githubusercontent.com/55564114/148491531-15d3ff61-b7cd-4f1f-a23b-d9b7abe01fb0.png)  

![스크린샷(121)](https://user-images.githubusercontent.com/55564114/148491586-6e84f1a0-0726-4249-b47c-85e72be886bc.png)
![스크린샷(122)](https://user-images.githubusercontent.com/55564114/148491630-e51ab0fd-f3d2-4999-bce7-cd0410ee3b74.png)  

![스크린샷(123)](https://user-images.githubusercontent.com/55564114/148491671-7c090491-0463-4107-8c3c-324d6c5c5935.png)  

---

궁금하신 부분은 댓글주시거나 메일 주시면 됩니다.🥰🥰  

---

