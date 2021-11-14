---
title:  "[블로그] 초보자도 쉽게 테마를 적용해서 깃허브 블로그 만들기"
excerpt: "테마를 적용하여 쉽게 깃허브 블로그를 만들어 봅시다."

categories:
  - Blog
tags:
  - [Blog ]

toc: true
toc_sticky: true
 
date: 2021-11-14
last_modified_at: 2021-11-14
---

# 0. 다른 블로그 포스팅과 다른 부분(fork 이용)

다른 블로그 보시면 이미 설치된 프로그램을 이용하거나 추가 설치(루비,jekyll)을 통해서 깃허브 블로그를 생성하시더라구여.  
  
  저는 프로그램 설치없이 깃허브 홈페이지를 이용해서 만들어 봤습니다.  
  저도 처음 블로그 생성할 때, 많이 막혀가지구 저와 같이 깃허브 블로그 만들분이 혹시 계실까봐 포스팅 합니다.  😆😆  

# 1. 깃허브 계정 생성 및 로그인

깃허브 블로그를 생성하실 분이라면 계정은 있으셔야 겠죠..? 🙄🙄  

# 2. 사용할 jekyll 테마 고르기 

- Jekyll 테마 제공 사이트
깃허브 블로그 만들기을 주제로 구글에 검색을 하시면 다양한 오픈소스 테마가 많아요. 그 중 많은 사람들이 사용하는 사이트 알려드릴게요.  

  - [http://jekyllthemes.org/](http://jekyllthemes.org/)
  - [https://jekyllthemes.io/free](https://jekyllthemes.io/free)
  - [http://themes.jekyllrc.org/](http://themes.jekyllrc.org/)
  - [https://github.com/topics/jekyll-theme](https://github.com/topics/jekyll-theme)
  

# 3. 선택한 테마로 깃허브 블로그 만들기 (fork 하기)

  일단, 제일 위에 있는 **http://jekyllthemes.org/** 으로 설명해드릴게요.  

  ![스크린샷(47)](https://user-images.githubusercontent.com/55564114/141670962-59202068-21f1-4587-b70f-9c17b3c64f6b.png)  

  ![스크린샷(48)](https://user-images.githubusercontent.com/55564114/141670998-e1a076d1-9b70-4591-bae9-7e9a26f8cf4b.png)  

  ![스크린샷(49)](https://user-images.githubusercontent.com/55564114/141671035-8ba740fe-0a5c-41b9-b7c0-6bc7f06c3e7e.png)  

  ![스크린샷(50)](https://user-images.githubusercontent.com/55564114/141671193-e86bf428-3ab2-41a3-9450-64be9f94c60f.png)  

  ![스크린샷(51)](https://user-images.githubusercontent.com/55564114/141671328-71aaa9ea-c9d9-44dc-8614-4b5d3aa81126.png)  


  1. 원하는 테마 선택
  2. 원하는 테마의 깃허브 사이트로 이동
  3. 우측 상단의 **"fork"** 클릭
  4. 생성이 되면, Setting에 들어가기
  5. Repository name 변경하기
    ex) UserName.github.io 
    UserName에 여러분의 닉네임을 넣어주시면 되요.
  6. 정상적으로 변경이 되면 다시 Setting에 들어가기
  7. Pages 에 들어가서 내 깃허브 블로그 들어가보기   


# 4. _config.yml 수정하기

![스크린샷(52)](https://user-images.githubusercontent.com/55564114/141671965-6d613947-0135-4fe2-be40-5ce12bd18ddc.png)  

![스크린샷(53)](https://user-images.githubusercontent.com/55564114/141672052-dd5b762a-0dbb-4a89-be9f-9fc2ac0d2707.png)  

1. 우측에 연필 🖍️ 모양을 클릭해서 수정모드 들어가기
2. ctrl + f 을 눌러서 **"url"** 검색 
3. url : http://UserName.github.io 으로 변경하기
  사실 전 이 부분 안넣어도 잘 되더라구여? 그래서 전 비워져 있어요. 😎  
4. 그 외, title , email 등등 하나씩 수정해보시면서 어느부분이 바뀌는지 확인해보세요.


---






