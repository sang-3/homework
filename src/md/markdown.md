# 마크다운 문법

장점

1. 문법이 쉽고 간결하다!
2. 관리가 쉽다!
3. 지원 가능한 플랫폼과 프로그램이 다양하다!

단점

1. 표준이 없다!
2. 모든 HTML 마크업을 대신하지 못한다!

# 제목(Header)

#의 갯수가 작을수록 더 중요한 제목이다!

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

마크다운에선 띄어쓰기 두번 하면 줄바꿈 처리가 된다!
만약 출력하는 환경에 따라서 줄바꿈이 안되는 경우 br 태그 사용하기!

동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세

# 강조(Emphasis)

_이텔릭_  
**두껍게**  
**_이텔릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>

# 목록(List)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
   1. 순서가 필요한 목록
   1. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
  - 순서가 필요하지 않은 목록
  - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록

# 링크(Links)

<a href="https://google.com">GOOGLE</a>
[GOOGLE](https://google.com)

<a href="https://naver.com" title="NAVER로 이동">NAVER</a>
[NAVER](https://naver.com 'NAVER로 이동')

<a href="https://naver.com" title="NAVER로 이동" target="_blank">NAVER</a>

# 이미지(Images)

링크와 이미지 차이는 맨 앞에 ! 붙어 있는냐 그렇지 않는냐 차이

![APPLE](https://search.pstatic.net/sunny/?src=https%3A%2F%2Fcdn.pixabay.com%2Fphoto%2F2020%2F03%2F31%2F15%2F04%2Fillustration-4988052_1280.png&type=sc960_832)

이미지에 링크 추가하기!
[![APPLE](https://search.pstatic.net/sunny/?src=https%3A%2F%2Fcdn.pixabay.com%2Fphoto%2F2020%2F03%2F31%2F15%2F04%2Fillustration-4988052_1280.png&type=sc960_832)](https://www.apple.com/kr/?afid=p240%7Cuc~p872_kw1808&cid=aos-kr-kwna-Brand-nbs)

# 인용문(BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장!

> 인용문을 작성하세요!

> > 중첩된 인용문

> > > 중중첩된 인용문 1  
> > > 중중첩된 인용문 2  
> > > 중중첩된 인용문 3

# 인라인(inline) 코드 강조

CSS에서 `background` 혹은
`background-image` 속성으로 요소에 배경
이미지를 삽입할 수 있습니다.

# 블록(block) 코드 강조

```html
<a href="https://www.google.co.kr/" target="_blank">GOOGLE</a>
```

```css
.list > li {
  position: absolute;
  top: 40px;
}
```

```javascript
function func() {
  let a = 'AAA';
  return a;
}
```

```bash
$ git commit -m 'Markdown'
```

```plaintext
동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세
```

# 표(Table)

position 속성
값 | 의미 | 기본값
--|:--:|--:
static | 기준 없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

# 원시 HTML(Raw HTML)

동해물과 <span style="text-decoration: underline;">백두산</span>이 마르고 닳도록<br />
하느님이 보우하사 우리나라 만세

<a href="https://naver.com" title="NAVER로 이동" target="_blank">NAVER</a>

<img width="70" src="" alt="" />

# 수평선(Horizontal Rule)

---

***

___
