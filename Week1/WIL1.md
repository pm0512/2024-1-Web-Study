# HTML
### Hyper Text Markup Language
- 기존의 문서들보다 hyper한 기능을 가지고 있는 문서를 의미
- 대표적으로 hyperlink나 markup 기능 등이 존재함
    - *hyperlink* : 문서나 웹 페이지 내에서 다른 문서나 웹 페이지로 이동할 수 있도록 하는 링크
    - *markup* : 문서의 구조를 정의하고 표현하는 언어, HTML에서는 태그를 사용하여 문서의 요소를 정의하고 이를 통해 텍스트의 구조, 이미지, 링크 등을 표현함
- HTML은 태그로 이루어진 markup 언어라고 정의 내릴 수 있음

#### 1. HTML 기본 문서 구조
`!+tab`을 이용하여 HTML 페이지를 만든 후 `live server` 확장 프로그램을 이용하여 실시간으로 HTML 파일을 볼 수 있음

```python
< h1 class="primary" > 제목 < /h1 >
```
- `h1` 태그명
- `class` 속성명
- `primary` 속성값
  
![alt text](<스크린샷 2024-05-14 160957.png>)
- `DOCTYPE` 어떤 버전으로 작성 되었는지 설명
- `html land=' '` 웹문서의 작성 언어가 무엇인지를 설명
   - en : 영어
   - ko : 한국어
- `head` html 태그의 자식 태그이며 웹 페이지 내에서는 보이지 않음
- `body` htm 태그의 자식 태그이며 웹 페이지 내에서 내용이 보여짐

#### 2. HTML 주석
```
< !--주석에 담을 내용을 적으세요-- >
```

#### 3. 글꼴 태그
- `< h1 > ~ < h6 >` Heading 
- `< p >` Paragraph

---
# CSS
### Canscading Style Sheets

#### 1. CSS 기본 구조
```python
h1{ color : blue; }
```
- `선택자`(h1) : 꾸미고 싶은 태그 선택
- `속성명`(color) : 꾸미고 싶은 태그의 어떤 것을 꾸밀지를 결정
- `속성값`(blue) : 속성명에 맞는 값을 의미

#### 2. CSS 적용 방법
(1) `Inline Style` 태그 내에서 style 지정

(2) `Internal Style Sheet` head 태그 안에 < style > 태그로 지정하여 사용

(3) `External Style` .css 활용

---
![alt text](웹스터디.png)