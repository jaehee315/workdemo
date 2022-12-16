# 스케줄

# 제목1

## 제목2

### 제목3

#### 제목4

##### 제목5

### BlockQuote

>This is a first blockquote
>
> > This is a second blockquote
>
> > This is a first blockquote

##목록 (LIST)

### 1)  순서가 있는 목록

1. 목록1
   1. 목록 1_1
   2. 목록 1_2
2. 목록2
   1. 목록2_1
   2. 목록2_2
3. 목록3
4. 목록4

#### 2) 순서가 없는 목록
- 목록
  - 목록1_1
  - 목록1_2
- 목록2
  - 목록2_1
  - 목록2_2
- 목록3


### 표만들기

- |(vetical val) : 테이블 표현
- : 정렬
- (---)헤더와 셀 구분


|  이름 |  주소 |     전화번호 |
| :-----: | :-----: | :-----------: |
| 홍길동 | 서울시 | 02-1234-1254 |
| 여진구 | 경기도 | 031-123-4568 |

### 코드(code)

#### 1) 인라인 코드(inline code)
- 백틱(\`)으로 강조할 내용을 감싼다.
repository에서 프로젝트의 설명을 부여해줄때 'READMe.md'을 사용한다.

#### 2) 블럭코드 (block code)
- 백틱(`) 3개로 html, css, java등 코드를 작성할때 사용한다.


```java
public static void main(String[] args) {
  System.out.println("Hello java");
}
```

### 글자 강조

**굵은 글씨**
_이텔릭_
_이텔릭_
~~취소선~~

<!— 실행 안됨 이유를 모르겠음—>

<u>밑줄</u>

### 링크(Links)

<!— 깃허브 사이트에서는 앞에 내 아이디를 넣어줘서 사이트가 안뜸 —>

[naver](https:www.naver.com/)

<!—깃허브 사이트에 a.txt 페이지로 이동—>

[link](a.txt)

<!— 외부링크 사용시 —>

다음 홈페이지 : <https://www.daum.net>

### 이미지(images)

![naver](https://s.pstatic.net/static/www/mobile/edit/20221214/cropImg_728x360_112955548973432846.jpeg)

![box](images/sp.jfif)

<!—이미지를 클릭했을때 하이퍼링크로 연동 —>

[![daum](images/20200723055344399.png)](https://www.daum.net/)


### 원시 HTML(Raw HTML)

<img src='images/20200723055344399.png' alt='daum'>