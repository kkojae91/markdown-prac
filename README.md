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
