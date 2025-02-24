## 텍스트 작성하기
### hn태그 
: 제목이나 주제를 나타내는 텍스트 표현 <br/>
: h = heading <br/>
: n = 숫자, 중요도에 따라 1 <b --- > 6 나뉘어짐<br/>
: hn 태그로 작성된 텍스트는 <b> 검색 엔진에서 키워드로 인식함!</b> <br/>
: h1 부터 단계적으로 사용해야함! - 중간에 빼먹은 숫자(e.g. h1, h2, h4 사용)가 있을 경우 검색 엔진이 단계적으로 태그를 검색하다가, 중간에 빠진 숫자가 있으면 빠진 숫자 이후의 태그는 검색하지 않음.
e.g.h1, h2, h4 사용 > h3이 빠졌으므로, h1, h2 까지 단계적으로 검색 이후 h4는 검색하지 않음.<br/>

### p 태그
: 본문의 문단을 작성할 때 사용 <br/>

### br 태그
: 문단에서 줄 바꿈할 때 사용<br/>

### blockquote 태그
: 출처에서 인용한 문단 단위의 텍스트 작성 시 사용<br/>
: 출처가 확실한 인용문은 cite 속성으로 출처 경로 명시<br/>
: 반드시 한 개 이상의 p 태그를 포함해야 함<br/>

### q 태그
: 문단 안에 텍스트 단위의 짧은 인용문을 작성할 때 사용<br/>
: q 태그를 사용한 콘텐츠는 출력 시 큰 따옴표로 묶임!<br/>

### ins, del 태그
- ins 태그 : 새로 추가된 텍스트임을 나타낼 때 사용(밑줄)
- del 태그 : 기존에 있던 텍스트가 삭제된 텍스트임을 나타낼 때 사용(취소선)

### sub, sup 태그
- sub 태그 : 아래 첨자
- sub 태그 : 위 첨자

<br/>
<br/>

## 그룹 짓기
### 공간 분할 태그
공간 분할 : 관련 있는 요소끼리 그룹 짓는 작업을 다른 영역과 분리한다는 의미 <br/>
-> 그룹짓기 작업을 수행하는 태그(div, span)를 공간 분할 태그라고도 함

### div 태그
: 블록 요소와 인라인 요소를 그룹으로 묶을 때 사용

- 블록 요소 : 사용할 때마다 줄 바꿈되는 태그로 작성한 코드
        - e.g. ) hn, p
- 인라인 요소 : 공간이 부족할 때만 줄 바꿈되는 태그
        - e.g. ) a, span

#### class 속성 : CSS 적용을 위한 식별자로 사용하는 속성

### span 태그
: 인라인 요소를 그룹으로 묶을 때 사용


## 목록 만들기
: 주로 목차와 메뉴 구성할 때 사용

### ul 태그
: 순서가 없는 비순서형 목록을 생성할 때 사용 <br/>
: 사용 시 목록 내용마다 글머리 기호가 붙음<br/>
: 목록 내용은 li 태그로 구성<br/>

### ol 태그
: 순서형 목록 생성할 때 사용<br/>
: 사용 시 목록 내용에 번호가 붙음<br/>
: 목록 내용은 li 태그로 구성<br/>

### dl 태그
: 정의형 목록* 생성할 때 사용<br/>
: 목록 내용은 용어(dt 태그) & 용어 설명(dd 태그)로 구성

* 정의형 목록 : 용어와 용어 설명을 나열한 형태의 목록<br/>

### ㅇ

