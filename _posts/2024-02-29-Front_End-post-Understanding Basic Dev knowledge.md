---
title: "Understanding Basic Dev knowledge"
excerpt: "Manhackdo Onboarding Course-1"

categories:
  - Front End
tags:
  - [HTML, CSS, JS]

permalink: /Front End/Understanding Basic Dev knowledge/

toc: true
toc_sticky: true

date: 2024-02-29
last_modified_at: 2024-02-29
---

<img width="697" alt="what-is-client-server-network" src="https://github.com/DaeSeo/DaeSeo.github.io/assets/118124409/163cbfab-0f7c-48c5-85e5-5d1faebc9c3f">

# 기본 개발 배경지식

##### 개발환경

개발을 하기 위해서는 code를 작성할 수 있는 tool이 필요하다.  코드는 기본적인 워드패드에서도 작성이 가능하지만 생산성을 높이기 위해 우리는 통합개발환경을 사용한다.



통합개발환경의 예로는,

1. VSCode

2. Atom

3. Webstorm

등이 존재하지만 이번 강의를 진행하는 동안은 VSCode를 사용하여 실습을 진행하도록 하겠다.



##### 웹 기술

웹은 일반적으로 HTML, CSS, Javascript 세가지 기술을 활용하여 제작이 가능하다.

그리고 위 기술로 작성된 코드는 웹브라우저(IE, Chrome, etc)을 활용하여 시각적으로 표현된다.



1. HTML
   
   HTML은 문서의 틀을 만드는 도구이다.
   
   다양한 태그들을 활용하는데, 여는태그, 닫는태그가 존재하며 태그 안에는 속성을 포함할 수 있다.
   
   ```html
   <P class="editor-note"> My Cat is very grumpy </p> #슬래쉬 -> 닫는태
   ```



2. CSS
   
   페이지의 색상이나 위치 등 기본 틀을 꾸미는 도구로써 CSS가 사용된다.
   
   ```css
   #third {
       color: green;
   }
   ```



    3. Javascript

        동적 페이지를 제작하기 위해서는 Javascript를 활용해야하는데 DOM API를 활용하여 HTML, CSS에 동적인 효과를 넣을 수 있다.







### 클라이언트 & 서버

![server](https://github.com/DaeSeo/DaeSeo.github.io/assets/118124409/128840ff-4abc-466b-9e5e-023e7e8a2f74)

클라이언트는 서버에 정보를 요청하는 사람으로 서버는 응답을 통해 정보를 제공한다.

클라이언트 개발자는 HTML, CSS. JS 등 시각적으로 확인이 가능한 인터페이스 등을 개발하는 역할을 담당한다.

반면 서버 개발자는 Back End, DB 등 일반 사용자에게는 보이지 않지만 서비스를 제공하는데 필요한 데이터를 저장, 가공, 제공 관련된 개발을 하는 역할을 담당한다.



### 네트워크

네트워크 기본지식으로는 IP, Domain, Port, Protocol이 있다.



1. IP: 인터넷의 주소체계 ex) 3.36.45.11

2. Domain:트워크 상  IP를 보기 쉽게 만든 주소 체계 ex) www.naver.com

3. Port: IP내에서 프로세스 구분을 위해 사용하는 번호로 IP주소가 가르키는 PC에 접속할 수 있는 통로(채널)을 의미한다. 포트 번호는 0~65,535까지 사용할 수 있며 그 중 0~1024번까지 포트 번호는 주요 통신을 위한 규약에 따라 이미 정해져 있다. ex) 22 = ssh, 80 =HTTP

4. Protocol: 서버와 클라이트가 어떤 방식을 통해 소통할것인가를 명시하는 통신 규약.
   
   a. HTTP
   
   b. HTTPS
   
   c. SSH
   
   e. FTP
   
   f. SFTP


끝.