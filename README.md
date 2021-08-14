# 제목(Header)

# 제목 1

## 제목 2

### 제목 3

#### 제목 4

##### 제목 5

###### 제목 6

# 문장(Paragraph)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

# 줄바꿈(Line Breaks)

1. 띄어쓰기 2번 넣어주면 줄 바꿈처리가 된다.
2. br tag를 사용해도 된다.

동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려 강산<br/>
대한 사람 대한으로 길이 보전하세

# 강조(Emphasis)

이텔릭체 : 언더바로 감싸준다. _이텔릭_  
두껍게 : 에스터리스크를 두번 넣고 감싸준다. **두껍게**  
이텔릭+두껍게 : **_이텔릭 + 두껍게_**  
취소선 : 물결표시(틸드) 두번 넣고 감싸준다. ~~취소선~~  
밑줄 : u tag로 감사준다. <u>밑줄</u>

# 목록(List)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록 (tab 키를 넣어주면 sub list 사용 가능)
   1. 순서가 필요한 목록
   1. 순서가 필요한 목록
   1. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록 (tab 키를 넣어주면 sub list 사용 가능)
  - 순서가 필요하지 않은 목록
  - 순서가 필요하지 않은 목록
  - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록

# 링크(Links)

- 링크로 이동 [텍스트]+(url)  
  <a href="https://google.com">GOOGLE</a>  
  [GOOGLE](https://google.com)

- 링크로 이동 + title 추가 [텍스트]+(url "title 텍스트")  
  <a href="https://naver.com" title="NAVER로 이동!">NAVER</a>  
  [NAVER](https://naver.com "NAVER로 이동!")

- 링크로 이동 Html target="\_blank" 마크다운 문법은 지원하지 않는다. a tag로 작성  
  <a href="https://naver.com" title="NAVER로 이동!" target="_blank">NAVER</a>

# 이미지(Images)

- 이미지 삽입 !+[대체 텍스트]+(url)
  ![HEROPY](https://img.etoday.co.kr/pto_db/2020/12/600/20201211102156_1553278_1200_600.jpg)

- 이미지 + 하이퍼링크 삽입 [!+[대체 텍스트]+(url)]+(url)
  [![NAVER](https://img.etoday.co.kr/pto_db/2020/12/600/20201211102156_1553278_1200_600.jpg)](https://naver.com)

# 인용문(BlockQuote)

> "> " 꺽세괄호 닫는 기호를 사용하고 띄어쓰기  
> 남의 말이나 글에서 직접 또는 간접적으로 따온 문장.  
> (네이버 국어 사전)

> 인용문을 작성하세요!
>
> > 중첩된 인용문에는 ">" 추가
> >
> > > 중중첩된 인용문에는 ">>" 추가
> > > 중중첩된 인용문에는 ">>" 추가
> > > 중중첩된 인용문에는 ">>" 추가

# 인라인(Inline) 코드 강조

빽틱 기호로 감사준다.  
CSS 에서 `background` 혹은
`background-image` 속성으로 요소에 배경 이미지를 삽입 할 수 있습니다.

# 블록(Block) 코드 강조

- 빽틱3개 사용하는 언어 빽틱3개 를 사용하면 블록 코드 강조를 사용할 수 있다.
- html

  ```html
  <a href="https://www.google.co.kr/">GOOGLE</a>
  ```

- css
  ```css
  .list > li {
    position: absolute;
    top: 30px;
  }
  ```
- javascript
  ```javascript
  function func() {
    const a = "AAA";
    return a;
  }
  ```
- bash(터미널)
  ```bash
  $ git commit -m 'Study Markdown'
  ```
- plaintext
  ```plaintext
    동해물과 백두산이 마르고 닳도록
    하느님이 보우하사 우리나라 만세
  ```

# 표(table)

:콜론으로 감싸면: 가운데 정렬  
콜론이 오른쪽에 있으면: 오른쪽 정렬  
기본값은 왼쪽 정렬  
복잡한 표는 만들 수 없다.

position 속성  
값 | 의미 | 기본값
--|:--:|--:
static | 기준 없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

# 원시 HTML(Raw HTML)

HTML 문법을 그대로 사용할 수 있다.

동해물과 <u>백두산</u>이 마르고 닳도록<br/>
하느님이 보우하사 우리나라 만세

<a href="https://naver.com" title="NAVER로 이동!" target="_blank">NAVER</a>

---

<img width="70" src="https://img.etoday.co.kr/pto_db/2020/12/600/20201211102156_1553278_1200_600.jpg" alt='NAVER'>

# 수평선(Horizontal Rule)

하이픈(-)을 세번 넣어주면된다.<br/>

---

에스터리스크를 세번 넣어주면된다.<br/>

---

언더바를 세번 넣어주면된다.

---
