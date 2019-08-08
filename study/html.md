## HTML
`HTML Tag`

[`Semantic Tag`](https://www.w3schools.com/html/html5_semantic_elements.asp)
  - `header`
  - `nav`
  - `aside`
  - `section`
  - `article`
  - `footer`



`non-Semantic Tag`
  - `div`



`heading`



`paragraph`
  - `br` : 줄바꿈
  - `hr` : 수평선 ` <hr size="5" width="50px" aligh="right" color="red" noshade> `
  (참고 : https://secretgd.tistory.com/106)
  
  - `p` : 



`font-style`
  - `b`, `strong` : 문자열 굵게.  차이? b : 글씨만 굵게. strong : 단락 내 문자 강조. semantic(?) 다른 음성 인식도구에서도 강조해서 읽어줌.
  <b>b 태그 적용</b>
  - `i`, `em` : <em>이탤릭체.</em>
  <br> i : 글씨만, em : 문자 강조
  - `del` : 취소선 <del> 취소선 </del>



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
  
  <ol type = "I">
  <li> 1번 </li>
  <li> 2번 </li>
  <li> 3번 </li>
  </ol>
  
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
<br><a href="python_function.md">function</a>

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