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
  - `i`, `em` : 이탤릭체.기울여서 표시
  i : 글씨만, em : 문자 강조
  - `del` : 취소선



`list`
  - `ol` + `li`
  - `ul` + `li`
`a`: 상대경로, 절대경로, `id`, `mailto`, `_blank`
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