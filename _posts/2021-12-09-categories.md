---
title: “[minimal mistakes] 카테고리 설정” # 실제 화면에 보이는 제목
categories: # 포스터의 소속 카테고리
  - github_blog
tag : # 포스터 태그
  - github
  - blog
last_modified_at: 2020-01-14T14:00:00+09:00 # 게시글 마지막 수정일

---



### ✅ _data -> navigation.yml 

---

![image-20211209180111040](https://user-images.githubusercontent.com/87456091/145367593-be24b031-ca43-4ad9-af3f-9de4bd6f146b.png)

- #### title

  - 상단 바에서 보이는 이름

- #### url

  - 두가지 방법

    - ##### 절대 경로 작성 

      -  https://hyojeong721.github.io/

    - ##### 상대 경로 작성 

      - 이 방법은 사전에 _pages 폴더를 만들어서 경로를 만들어줘야 함! 

      - ex) /cagegories/ : _pages -> category-archive.md 파일이 존재!

      - category-archive.md 안에 또 양식이 있음!

      - ```
        ---
        title: "Posts by Category" 
        layout: categories
        permalink: /categories/  
        author_profile: true
        ---
        ```

        

