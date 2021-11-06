# Spotify WebSite
### 웹페이지 어떤식으로 영역을 나눌지 생각하고 시작하기!!
[>> 내가만든 spotify 페이지 바로가기 ](https://spotify-website.hyodii.repl.co/)

<br>

- <b>웹사이트 만들 때 div 대신 시멘틱 태그 사용하기!</b> <br>
`<article>` `<aside>` `<details>` `<figcaption>` `<figure>` `<footer>` <br> `<header>` `<main>` `<mark>` `<nav>` `<section>` `<summary>` `<time>` <br>
참고👀 : https://www.w3schools.com/html/html5_semantic_elements.asp 
<br>

 - <b>상대경로 절대경로 ⚖</b>

절대 경로:  최초의 시작점으로 경유한 경로를 전부 기입하는 방식입니다.

상대 경로:  현재 위치한곳을 기준으로해서 '그곳'의 위치



예 ) C:\users\documents\Desktop\코딩누나\first-project\image => 절대경로

       내가 index.html에 있다면, ./image => 상대경로 

예2) 내가 index.html에 있는데 first-project로 나가고싶다면 

          C:\users\documents\Desktop\코딩누나\first-project =>절대경로

          ../first-project => 상대경로 

        ..(점)을 두번쓰면 한단계 전까지만 가져온다 .(점)을 한번쓰면 현재 경로를 다 가져온다 
        
- <b>단위정리</b>

  - px : 절대적인 값임, 다른값이 영항을 받지 않음
  - em: 상위요소 폰트크기 기준이다. 폰트가 12px이면 1em 은 12px. 화면사이즈에따라 반응형웹을 만들때 쓰기 좋다 
  - rem: em이랑 비슷함 But, html태그(root)의 폰트크기 기준이다. 내자신이 12px이더라도 html이 20px이면 1rem 은 20px 
  - % : 상위요소크기 기준으로 % 따짐

- <b>버튼 hover 시 버튼 커지게 하는 법</b> <br>
  `transform: scale()`
  
- <b>footer</b> <br>

시작 전 영역 나누기 중요! → 그림그리기
  
  
  
