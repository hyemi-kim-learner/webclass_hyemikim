# HTML, CSS, JS 기초

## HTML

> HTML :  Hyper Text Markup Language - 마크업(표시) 언어
> 
> 웹페이지의 구조를 표시
> 
> 웹페이지의 콘텐츠를 표시
> 


###HTML Elements

> Element: 요소 - 의미적
>
> Tag: 태그 - 기술적
>
> Syntax 문법: <> 로 감싸줌, 소문자 사용
> 
> 시작태그와 종료태그 세트로 구성됨
```

  <tagname>contents</tagename>
```

> [예외] 시작태그만 존재하는 경우가 있음 = 빈 태그 (Empty Elment)


> 포함관계 (Nested) 
```
<body> 
  <div>  
    text
  </div> 
</body>
```

###HTML Attributes

> HTML 속성
> HTML 요소의 부가 정보
> 속성 name = "속성value"

> 'a' 태그 : 링크로 연결
> 
```
<a href="http://www.naver.com"> naver </a>

```

###제목 테그
> heading -> h
> h1 ~ h6 "h1이 가장 큰 제목"

###HTML 기본 구조
'''
<!DOCTYPE html> - 1
<html> - 2
  <head> - 3
    <meta charset="utf-8"> - 4
    <title>My test page</title> - 5
  </head>
  <body> - 6
    <p>This is my page</p>
  </body>
</html>

'''
1. 웹 문서의 버전 : HTML5
2. HTML 문서의 가장 바깥쪽 요소
3. 웹 문서를 설명하는 정보가 담기는 영역 요소 *실제 컨텐츠는 아니지만 해당 문서를 설명하는 정보
4. 웹 문서의 정보 표시하는 요소
5. 웹 문서의 제목을 표시하는 요소
6. 웹 문서의 콘텐츠 요소들이 담기는 영역 요소


###단락태그

> 단락 표시
> 단락과 단락 사이를 구분하는 수평선
```
<hr> - Horizontal Rule
```
> 단락을 구분하지 않고 줄 바꿈만 하는 태그
'''

<br> - Break
```2

