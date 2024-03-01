---
title: "Basic HTML-1 TWTWTW"
excerpt: "Manhackdo Onboarding Course-2"

categories:
  - Front End
tags:
  - [HTML]

permalink: /Front End/Basic HTML-1/

toc: true
toc_sticky: true

date: 2024-03-01
last_modified_at: 2024-03-01
---

# HTML Basic

<img width="1785" alt="html_logo" src="https://github.com/DaeSeo/DaeSeo.github.io/assets/118124409/f1fcb8d8-7fcd-48ff-b5b9-c1e52ab31600">


### HTML 구조 파악

HTML 코드는 기본적으로 tag를 통해서 이루어져있다.

태그 안에는 해당 태그에 속성을 보여주는  class(Attribute)가 존재하며 대부분의 태그는 닫힐때 닫는 태그를 통해 해당 코드가 끝이났음을 명시해줘야한다. 단 몇가지 태그에 한해서는 닫는태그가 불필요하다(ex, img)



##### 코드 기본구조

```html
<p class="editor-note"> My Cat is very grumpy </P>  
```

위 코드에서는 p태그를 이용하였으며 속성값으로 edictor-note를 제공했다. 해당 태그의 내용은 오픈태그 바로 뒤 "My cat is very grumpy" 이며 이후 닫는 태그 </P>가 위치한다.

아래는 기본적인 html 구조이다.

```html
<!DOCTYPE html>
<html lang="en">  <!html 언어 명시>
<head> <!head태그 시작>
  <meta charset="UTF-8"> <!인코딩방식(매타태그)>
  <meta http-equiv="X-UA-Compatible" content="IE=edge">  <!IE문서모드, http 헤더 제>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>

</body>
</html>    
```



### HTML 기본 태그 정리



##### html 태그

```html
<html></html>
```

<body></body>

기본적으로 문서의 범위를 알려주는 태그로 시작과 끝을 태그로 열고 닫아준다.

속성으로는 lang: 문서가 어떤 언어로 작성되어있는지 명시 ex) ko, en



##### head 태그

```html
<head></head>
```

<body></body>

<body></body>

문서에 대한 메타 데이터를 넣는 태그

head 태그 내에는 meta, link, title 태그 등이 포함됨.



##### body 태그

```html
<body></body>
```

실제 화면에 표시되는 내용을 넣는 태그.



##### meta 태그

```html
<meta class="값" />  <!닫는 태그 없음>
```

메타 데이터를 설정하기 위한 태그로 하나의 태그로 열고 닫는다.



###### meta 태그 속성

| 속성         | 값                                                                                   | 설명                             |
| ---------- | ----------------------------------------------------------------------------------- |:------------------------------:|
| charset    | UTF-8<br/>EUC-KR<br/>등등 인코딩 방식                                                      | HTML문서의 문자 인코딩을 지정             |
| content    | 연관된 값                                                                               | http-equiv 또는 이름 속성과 연관된 값을 지정 |
| http-equiv | content-security-policy<br/>content-type<br/>default-style<br/>refresh              | 콘텐츠 속성의 정보 / 값에 대한 HTTP 헤더를 제공 |
| name       | application-name<br/>author<br/>description<br/>generator<br/>keywords<br/>viewport | 메타 데이터의 이름을 지정                 |

참고블로그

[[HTML기초문법] 17강 meta태그와 viewport - 오쌤의 니가스터디](https://ossam5.tistory.com/118)



##### link 태그

```html
<link rel="icon" href="favicon.ico" />
<link rel="stylesheet" href="style.css" />
```

link 태그를 활용하여 CSS, 또는 Favicon을 가져온다.

rel: 현재 html 문서와의 관계 정의

href: 데이터의 경로 표시



##### title 태그

```html
<title>Document</title>
```

문서의 제목을 설정하는 태그.



##### script 태그

```html
<script src="index.js"></script>
```

자바스크립트 파일을 연결하는 사용하는 태그

src: 자바스크립트 파일 경로





끝.