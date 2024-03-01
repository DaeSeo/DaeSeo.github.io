---
title: "Basic HTML-2"
excerpt: "Manhackdo Onboarding Course-3"

categories:
  - Front End
tags:
  - [HTML]

permalink: /Front End/Basic HTML-2/

toc: true
toc_sticky: true

date: 2024-03-01
last_modified_at: 2024-03-01
---

# HTML Basic

<img width="1785" alt="html_logo" src="https://github.com/DaeSeo/DaeSeo.github.io/assets/118124409/f1fcb8d8-7fcd-48ff-b5b9-c1e52ab31600">


### HTML 주요 태그 & 사전지식

html문법을 작성하는데 있어서 빈번하게 사용되는 주요 태그들과 필요한 사전지식을 다루어보겠다.
<br/>

### 사전지식


##### 1. 주석

주석은 일종의 코멘트로 화면에 표시되거나 기능을 수행하지는 않지만 작성된 코드를 설명하기 위해 주로 사용됨

```html
<!--html 주석 -->
```

##### 2. 절대경로, 상대경로

컴퓨터가 원하는 파일을 인식하는 두가지 방법이다.
* 절대경로: 모든 루트를 적은 경로
* 상대경로: 현재 경로를 기준으로 상대적인 경로

<br/>
<br/>
<br/>

### 주요 태그

주요태그는 MDN 홈페이지와 HTML Ref(3schools)를 참고하자.

[Mdn web docs](https://developer.mozilla.org/ko/docs/Web/HTML/Element)

[3 schools](https://www.w3schools.com/tags/default.asp)

##### div 태그

```html
<div></div>
```
대부분의 레이아웃은 div태그로 구성한다. CSS와 JS 특정 부분을 제어할때 유용하며 class와 id 속성을 함께 사용하는것이 일반적이다.

##### h1~h6 태그

```html
<h1>안녕</h1>
```
제목이나 강조하고싶은 부분을 나타내는 태그. h1의 폰트사이즈가 가장 크며 숫자가 커질수록 사이즈가 작아진다.


##### img 태그

```html
<img src="" alt="" />
```
이미지를 보여줄 수 있는 기능을 하는 태그이다.
* src: 이미지의 경로
* alt: 이미지 오류시 대신 나타낼 문구


##### input 태그

```html
<input type="" />
```
사용자에게 입력을 받는 태그값으로 type으로 속성값을 받는다.
* text: 일반 텍스트를 입력 받을 수 있습니다.
* password: 패스워드를 입력 받을 수 있도록, 입력 값이 화면에 보여지지 않도록 합니다.
* submit: \<form></form> 태그 내에 입력된 데이터를 서버로 전달해 줍니다.
* button: 버튼을 생성해 줍니다.
* checkbox: 체크박스 형태의 입력을 받을 수 있습니다.
* radio: 라디오 버튼 형태의 입력을 받을 수 있습니다.
* reset: \<form> 태그 안의 사용자 입력을 초기화 합니다.
  
출처: https://hianna.tistory.com/309 [어제 오늘 내일:티스토리]


##### button 태그

```html
<button>클릭</button>
```
사용자가 클릭할 수 있는 버튼을 만드는 태그이다.


##### a 태그

```html
<a href="" target=""> </a>
```
다른 구획 또는 페이지로 이동할때 사용하는 태그이다.
* href: 이동할 페이지의 링크(하이퍼링크)
* target: 페이지 이동 방식
  * _blank: 새 창으로 이동


##### span 태그

```html
<span></span>
```
CSS, JS를 적용시키기위해 보이지 않은 의미상 존재 태그


##### ul, ol, li 태그

```html
<ul>
  <li>1</li>
  <li>2</li>
  <li>3</li>
</ul>
```
리스트를 표현하기 위해 사용하는 태그
* ol(ordered list): 순서가 있는 리스트
* ul(unordered list): 순서가 없는 리스트
* li: 리스트 요소


##### form 태그

```html
<from action="" method="" target="">
</form> 
```
사용자 입력을 받아 서버에 네트워크를 요청할때 사용하는 태그
* action: 입력받은 데이터를 처리할 URL
* method: HTTP 메서드 ex) GET, POST
* target: 링크 이동 방법 ex) _self, _blank
  
<br/>
<br/>
<br/>

### 태그 분류

1. Block Element
  * 하나의 태그가 브라우저에서 좌우 공간을 다 차지하면서 독립적인 덩어리 공간을 가지고 있는 요소이다.
    * 블럭요소: \<div>,\<table>,\<h1>~\<h6>,\<p>,\<form>,\<ul>,\<ol>,\<li>,\<dl>,\<dt>,\<dd>,\<pre>,\<blockquote> 등

  
2. Inline Element
  * 하나의 태그가 브라우저에서 실제로 코딩된 그 영역만 차지하며 좌우로 다른 태그가 나란히 위치할 수 있는 요소이다. 행 안의 일부분으로 생각할 수 있으며 텍스트 레벨 요소라고도 한다.
    * 인라인요소: \<span>,\<a>,\<br>,\<em>,\<strong>,\<input>,\<label>,\<img>
  
<img width="626" alt="elements" src="https://github.com/DaeSeo/DaeSeo.github.io/assets/118124409/225c8b95-d2b1-4eba-a7d5-64443dde0f70">
  
<br/>
<br/>
<br/>

### 시맨틱 태그

![symentic_tag](https://github.com/DaeSeo/DaeSeo.github.io/assets/118124409/521b700a-9cce-4893-9411-daf1502eb8ec)


시맨틱 태그란, 태그에 의미를 부여해서 브라우저와 개발자가 의미를 쉽게 알 수 있도록 돕는 태그로 대부분 \<div>, \<span> 태그에 class, id 속성을 이용해 표현한다.


<br/>
<br/>
<br/>


### 크로스브라우징

크로스브라우징이란, 서로 다른 웹 브라우저에서도 동일한 UX/UI를 구현하기 위한 기술로 모든 브라우저에서 정상적으로 작동하게 하는 작업이다.


* Can I use: 브라우저 호환성 검사 [Can I Use](https://caniuse.com/)
* Markup Validation Service: 호한성 검사 [W3](https://validator.w3.org/)
* MDN: 학습도구 등 [MDN](https://developer.mozilla.org/ko/)


끝.