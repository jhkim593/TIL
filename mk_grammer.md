파일명 규칙



1.한글 x

2.띄어쓰기 X->언더바

3.특수문자 지양 



~ :home directory

pwd, ls cd, touch

. .=> 상위 디렉토리

. ==>현재디렉토리

컨트롤 l :지우기



`ls -al` 모든 파일을 표시 숨김 파일 까지

`git status`: git 상태를 볼 수있다

`git add a.txt b.txt`  스테이징 area로 들어간다

`git log`: commit 확인 가능하다

마우스 휠로 복붙 가능





## 마크다운 문법

##### 제목 (heading)

문서의 구조를 잡기위해 활용 된다. 제목의 레벨에 맞춰 `#`으로 표현한다. 

### 제목3

#### 제목4

##### 제목5   

컨트롤  + 1,2,3,4,5

----

`---` :하이픈 3개 이상이면 헤드라인을 그을 수 있다.



목록 

- `-` :스페이스 바로 목록표시  
- 순서가 없다 엔터로 계속늘림
  - `tab`으로 서브 목록
- shift tab으로 나 올 수 있다
- 목록 끝낼 때 엔터 엔터로 나올 수 있다.



 순서가 있는 목록 숫자 띄어쓰기 `숫자.`

1.tab하면 서브 목록 관리

​	1.shift tab으로 나오고

2.끝낼때 엔터엔터

---

### 코드 블럭

```java
int num=10;
```

1번 왼쪽 문자 세개로 실행하고 문자로 찾아서 사용가능  1번왼쪽문자 세개 엔터 후 나중에 언어 선택해도됨



---

#### 표

| 순번 | 이름   |      |
| :--- | ------ | ---- |
| 1    | 김준호 |      |
| 2    | 홍길동 |      |
| 3    | 박명희 |      |



---

이미지

[]:이미지가 로드 되지 않았을 때 대체텍스트 ()안에 picsum 주소 입력

아래는 picsum을 이용한 외부 사진

<img src="https://picsum.photos/200/300" alt="image" style="zoom:25%;" />



내 로컬 이미지는 마크다운 저장 위치에 폴더가 바로 생성된다.

![이미지 샘풀](mk_grammer.assets/이미지 샘풀.png)

---

#### 링크

[구글](https://google.com)  로이동해보자

`[]()`대괄호 이름 소괄호 링크

`.`은 현재위치를 뜻하므로 아래 구문이 가능

[폴더](./mk_grammer.assets) 에 마크 다운 이미지가 있습니다.

---

기타 

*ㅇㄴㅋ* `**`

**ㅇㄴ** 굵게`****`

~~ㅇㄴ~~ `~~~~`

> `>+space`



[공유abit.ly](https://abit.ly)  url shorten해준다.--

[마크다운참고](https://guides.github.com/features/mastering-markdown/)

