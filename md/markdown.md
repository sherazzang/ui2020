# 마크다운 문법(syntax) 학습하기

## 마크다운 소개
## 마크다운 문법


### 제목(Header) 

# 제목 <h1>
## 제목 <h2>
###### 제목 <h3>


### 강조(Emphasis)

이탤릭 *이탤릭* _이탤릭_
볼드 **볼드** __볼드__
취소선 ~~취소선~~
마크다운 문법안에서 html 문법 사용 가능. 하지만 추천하지 않는다.<u style="color:red">underline</u>


### 목록(List)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
   - 순서가 필요하지 않은 목록
   - 순서가 필요하지 않은 목록
1. 순서가 필요한 목록

### 링크(Links)

[google](https://google.com)
[naver](https://www.naver.com "링크설명")
[상대적 참조](../user/login)

### 이미지(imgages)
![대체텍스트](http://www.gstatic.com/webp/gallery/5.jpg "링크설명")


### 이미지에 링크
[![대체텍스트](http://www.gstatic.com/webp/gallery/5.jpg )](https://kr.vuejs.org/)


### 코드(Code)강조
`bacaground` 혹은 `background-image` 속성으로 요소에 배경이미지 삽입 가능

###  블록(block) 코드 강조
```html
<a href="https://www.google.co.kr/" target="_blank">GOOGLE</a>
```

### 표(table)
| 값 | 의미 | 기본값
| --- | :---: | ---:|
| `static` | 유형(기준) 없음/ 배치 불가능 | `static` |
| `ralative` | 요소 자신을 기준으로 배치 | `relative` |
| `absolute` | 위치 상 부모(조상)요소를 기준으로 배치 | `absolute` |
| `fixed` | 브라우저 창을기준으로 배치 | `fixed` |

### 인용문(BlockQuote)
>인용문
>>인용문
>>>인용문

### 원시 HTML(Raw HTML)
마크다운 문법이 아닌 HTML 문법을 상용할 수 있다.
<u>마크다운에서 지원하지 않는 기능</u>을 사용할때 유용함
<img width="150" src="http://www.gstatic.com/webp/gallery/4.jpg" alt="prunus">
![prunus](http://www.gstatic.com/webp/gallery/4.jpg)

### 수평선(Horizontal Rule)
각 기호를 3개이상 입력.
___
(Hyphens)

***
(Asterisks)

___
(underscores)


### 줄바꿈(Line Breaks)
띄어쓰기 두번 이 줄바꿈인데 줄바꿈이 동작하지 않는 환경에서는 <br> 을 활용한다.

동해물과 백두산이 마르고 닳도록  하느님이 보우하사<br> 우리나라만세   