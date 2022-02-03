
#사이드바 카테고리

# 카테고리 정보 

    ● 앱인벤터 
        ┗ 작품 
            ○ 포스팅 카테고리 : AppInventor_dev
            ○ _pages/categories : /categories/appinventor_dev
        ┗ 블록설명
            ○ 포스팅 카테고리 : AppInventor_block
            ○ _pages/categories : /categories/appinventor_block
    
    ● 스크래치 
        ┗ 작품 
            ○ 포스팅 카테고리 : Scratch_dev
            ○ _pages/categories : /categories/scratch_dev
        ┗ 블록설명
            ○ 포스팅 카테고리 : Scratch_block
            ○ _pages/categories : /categories/scratch_block

    ● 앱 개발 
        ┗ Android 
            ○ 포스팅 카테고리 : Android_Studio
            ○ _pages/categories : /categories/android_studio
        ┗ Flutter
            ○ 포스팅 카테고리 : Flutter
            ○ _pages/categories : /categories/flutter

    ● 블로그 
        ┗ 개발 
            ○ 포스팅 카테고리 : Blog_dev
            ○ _pages/categories : /categories/blog_dev
        ┗ 이야기
            ○ 포스팅 카테고리 : Blog_story
            ○ _pages/categories : /categories/blog_story
        ┗ 2019년도
            ○ 포스팅 카테고리 : Blog_dev_2019
            ○ _pages/categories : /categories/blog_dev_2019
        ┗ 2020년도
            ○ 포스팅 카테고리 : Blog_dev_2020
            ○ _pages/categories : /categories/blog_dev_2020

----------------------------------------------------------------------------------------------------

# 사이드바 카테고리 추가 방법

    3.1 카테고리 추가
        ● _pages/_categories 안에 카테고리 페이지 파일 생성 
        ● 내용 : 
<!--
ex)
파일명 : category-AppInventor_block 
내용 : 
    ---
    title: "앱인벤터"  ★ 타이틀 변경
    layout: archive  <- 뭔지 모름 안바꿈 
    permalink: categories/appinventor_block  ★ appinventor_block 부분만 변경, 기억해둘 것.
    author_profile: true <- 뭔지 모름 안바꿈
    sidebar_main: true <- 뭔지 모름 안바꿈
    ---

    {% assign posts = site.categories.AppInventor_block %} ★AppInventor_block 부분만 변경, 포스팅 안에 카테고리랑 같아야함.
    {% for post in posts %} {% include archive-single2.html type=page.entries_layout %} {% endfor %}
-->

    3.2 사이드바 카테고리 레이아웃 수정 
        ● _includes/nav_list_sidebar 안에 수정
        ● 내용 :
<!--
 <li>
       <span class="nav__sub-title">앱인벤터</span> ★큰 카테고리(클릭 안됨) , 앱인벤터 : 수정
            <ul>
                {% for category in site.categories %}
                    {% if category[0] == "AppInventor_dev" %} ★AppInventor_dev:포스팅 안에 카테고리 및 수정
                        <li><a href="/categories/appinventor_dev" class="">작품 ({{category[1].size}})</a></li> ★ 작은 카테고리(클릭 됨) , "작품" 수정
                    {% endif %}
                {% endfor %}
            </ul>
            <ul>
                {% for category in site.categories %}
                    {% if category[0] == "AppInventor_block" %}
                        <li><a href="/categories/appinventor_block" class="">블록설명 ({{category[1].size}})</a></li>
                    {% endif %}
                {% endfor %}
            </ul>
</li>
-->

----------------------------------------------------------------------------------------------------

# 사이드바 카테고리 파일 위치
레이아웃 수정 위치 : _includes/nav_list_sidebar

# 사이드바 카테고리 관련 파일 위치
파일 위치 : _pages/categories/...
파일 위치 : _includes/nav_list_sidebar




