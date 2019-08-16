## HTML
`HTML Tag`

[`Semantic Tag`](https://www.w3schools.com/html/html5_semantic_elements.asp)
  - `header`
  - `nav`
  - `aside`
  - `section`
  - `article`
  - `footer`


<!DOCTYPE html>
<html lang="ko">
<head>
    <title>HAEDAL</title>
    <style type="text/css">
    body{width:440px;}
    header, nav, section, article, aside, footer{display:block; width:400px; margin:4px; padding:4px; background-color:#dbdbdb; text-align:center; border-radius: 5px}
    section{float:left; width:280px; height:200px;}
    article{width:264px; background-color:#efefef; height:164px; line-height: 164px; border-radius: 5px}
    aside{float:left; width:104px; height:200px;}
    footer{overflow:hidden;}
    </style>
</head>
<body>
    <header>header</header>
    <nav>nav</nav>
    <section>
    section
        <article>article</article>
    </section>
<aside>aside</aside>
<footer>footer</footer>
</body>
</html>



`non-Semantic Tag`
  - `div`



`heading`

```
<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>
<h4>This is heading 4</h4>
<h5>This is heading 5</h5>
<h6>This is heading 6</h6>
```

<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>
<h4>This is heading 4</h4>
<h5>This is heading 5</h5>
<h6>This is heading 6</h6>


<br>

`paragraph`
  - `br` : 줄바꿈
  - `hr` : 수평선 ` <hr size="5" width="50px" aligh="right" color="red" noshade> `
  (참고 : https://secretgd.tistory.com/106)
  
  - `p` : 



`font-style`
  - `b`, `strong` : 문자열을 굵게 강조하는 태그.
  
    <b>b 태그 적용</b>
  <br>
    <strong> strong 태그 적용 </strong>
    
    두 태그의 차이가 보이시나요? 사실상 눈에 보이는 차이는 없습니다.
    하지만 
    
    차이? b : 글씨만 굵게.
    strong : 단락 내 문자 강조. semantic(?) 다른 음성 인식도구에서도 강조해서 읽어줌.
  
  
  - `i`, `em` :
  
    <i>i 태그 적용</i>
    <br>
    <em>em 태그 적용</em>
    
    `<i>` 태그와 `<em>` 태그의 차이는 `<b>` 태그와 `<strong>` 태그의 차이와 같습니다.
    <br> i : 글씨만, em : 문자 강조
  - `del` : 취소선을 표시하는 태그.
   <br><del> del 태그 적용 </del>



`list`


  - `ol` + `li` : ordered list. 숫자나 알파벳 등 순서가 있는 목록
  
  `<li>` : list item
  ```
  <ol>
      <li> 1번 </li>
      <li> 2번 </li>
      <li> 3번 </li>
  </ol>
  ```
  <ol>
  <li> 1번 </li>
  <li> 2번 </li>
  <li> 3번 </li>
  </ol>
  
  ```
  <ol type = "I">
      <li> 1번 </li>
      <li> 2번 </li>
      <li> 3번 </li>
  </ol>
  ```
  <ol type = "I">
  <li> 1번 </li>
  <li> 2번 </li>
  <li> 3번 </li>
  </ol>
  
  ```
  <ol start="3">
      <li> 1번 </li>
      <li> 2번 </li>
      <li> 3번 </li>
  </ol>
  ```
  
  <ol start="3">
  <li> 1번 </li>
  <li> 2번 </li>
  <li> 3번 </li>
  </ol>
  
  - `ul` + `li` : unordered list. 순서가 필요없는 항목
  
  ```
  <ul>
      <li> 1번 </li>
      <li> 2번 </li>
      <li> 3번 </li>
  </ul>
  ```
  <ul>
  <li> 1번 </li>
  <li> 2번 </li>
  <li> 3번 </li>
  </ul>
`a`: 상대경로, 절대경로

참고링크 : https://electronic-moongchi.tistory.com/87

`<a href="python_function.md">python_function</a>`
<br><a href="python_function.md" title="title 속성">python_function</a>


`id`, `mailto`, `_blank`
`media`
  - `img`
  - `iframe`



`form`
  - `input` : text, password, submit

추가적인 학습 : [MDN HTML Tag](https://developer.mozilla.org/en-US/docs/Web/HTML/Element), [poiemaweb](https://poiemaweb.com/), [velopert](https://velopert.com)




`fake_naver.html` : `form`태그와 `query`를 활용해 fake 네이버 검색창 만들기
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Document</title>
</head>
<body>
  <form action="https://search.naver.com/search.naver">
    <input type="text" name="query">
    <input type="submit">
  </form>
</body>
</html>
```