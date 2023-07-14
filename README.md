# 제목(Header)

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

# 줄바꿈(Line Breaks)

동해물과 백두산이 마르고 닳도록<br/>
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려 강산 \
대한 사람 대한으로 길이 보전하세

# 강조(Emphasis)

_이텔릭_  
**두껍게**  
**_이텔릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>  

# 목록(List)

1. 순서가 필요한 목록1
1. 순서가 필요한 목록2
1. 순서가 필요한 목록3
    1. 순서가 필요한 목록3-1
    1. 순서가 필요한 목록3-2
1. 순서가 필요한 목록4

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록2
- 순서가 필요하지 않은 목록3
    - 순서가 필요하지 않은 목록3-1
    - 순서가 필요하지 않은 목록3-2
- 순서가 필요하지 않은 목록4

# 링크(Links)

<a href="https://google.com">Google</a>

[Google](https://google.com)

<a href="https://naver.com" title="Naver로 이동!">Naver</a>

[Naver](https://naver.com "Naver로 이동!")

<a href="https://naver.com" title="Naver로 이동!" target="_blank">Naver</a>

# 이미지(Images)
느낌표를 앞에 추가하면 됨
![Dolphin](https://tistory1.daumcdn.net/tistory/3236913/attach/84183ad4eb034e5188a54147765e4529)

이미지눌러서 해당 주소로 이동- 대괄호안에 이미지코드 전부 넣기
[![Dolphin](https://tistory1.daumcdn.net/tistory/3236913/attach/84183ad4eb034e5188a54147765e4529)](https://wakestand.tistory.com/667)

# 인용문(BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장  
> (네이버 국어 사전)

> 인용문 중첩사용해보기
>> 중첩된 인용문1
>>> 중중첩된 인용문1
>>>> 중중중첩된 인용문1

# 인라인(inline) 코드 강조
백틱(`)기호 사용

CSS에서 `background` 속성으로 요소에
`background-image` 속성으로 요소에 배경 이미지 삽입 가능하다

# 블록(block) 코드 강조
백틱(`) 기호 3번 사용
```html
<a href="https://www.google.com" target="_blank">Google</a> 
```

```bash
$ git init
```

```plaintext
안녕하세요
```

# 표(Table)
vertical bar(|)와 하이픈(-) 사용  

position 속성(기본적으로 왼쪽 정렬)

값 | 의미 | 기본 값
--|--|--|
static | 기준 없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X


position 속성(정렬)- : 사용  
:--: - 가운데 정렬
--: - 오른쪽 정렬

값 | 의미 | 기본 값
--|:--:|--:|
static | 기준 없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

# 원시 HTML(Raw HTML)
동해물과 <u>백두산</u>이 마르고 닳도록<br/>
하느님이 <span style = "text-decoration: underline;">보우하사</span> 우리나라 만세  
무궁화 삼천리 화려 강산 \
대한 사람 대한으로 길이 보전하세

# 수평선(Horizontal Rule)
'---' & '___' & '***' 사용

---
***
___