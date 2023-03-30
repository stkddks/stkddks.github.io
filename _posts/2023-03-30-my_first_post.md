---
title:  "[Github 블로그] 나의 첫번째 포스팅"
excerpt: "Github 블로그에 하는 나의 첫번째 포스팅. "

categories:
  - Blog
tags:
  - [Blog, stkddks, Github, Git]

toc: true
toc_sticky: true
 
date: 2023-03-30
last_modified_at: 2023-03-30
---

# 0. 머릿말
머릿말을 작성합니다.

🌝 **<u>공지 사항</u>** 지각하지 말고 준비물 챙겨오세요!
{: .notice--primary} 

<div class="notice--primary" markdown="1">
안에 `코드`도 넣을 수 있다. 아래처럼!
    ```c++
std::cout << "Hello. World! >> std::endl;
    ``` 

- C++ 열심히
- 공부하자
</div>

<div class="notice">
  <h4>Message</h4>
  <p>A basic message.</p>
</div>

{% capture notice-2 %}  <!--notice-2 라는 변수에 다음 텍스트 문단을 문자열로 저장한다.-->  
#### New Site Features

* You can now have cover images on blog pages
* Drafts will now auto-save while writing
{% endcapture %}  <!--캡처 끝! 여기까지의 텍스트를 변수에 저장-->

<div class="notice">
  {{ notice-2 | markdownify }} <!--div 태그 사이에 notice-2 객체를 출력하되 markdownify 한다. 즉 마크다운 화-->
</div>