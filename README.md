# 제목1

## 제목2

### 제목3

#### 제목4

##### 제목5

###### 제목 6

1. 순서가 있는 목록
2. 순서가 있는 목록 1.순서가 있는 목록

-순서가 없는 목록

- 대쉬 (hyphen)

* 더하기(plus sign)

- 별표(asterisk)

### 링크(link)

[구글](https://www.gogle.com)  
[네이버](https://www.naver.com)  
[구글홈페이지]<https://www.gogle.com>  
[네이버 홈페이지]<https://www.naver.com>

### 이미지(images)

![김민재](https://search.pstatic.net/common?type=b&size=216&quality=100&direct=true&src=http%3A%2F%2Fsstatic.naver.net%2Fpeople%2F1%2F202206281819545621.png)

[![네이버](https://search.pstatic.net/common/?src=http%3A%2F%2Fimgnews.naver.net%2Fimage%2F5097%2F2019%2F07%2F25%2F368292_267336_3425_20190725113616536.jpg&type=l340_165)](https://www.naver.com)

![가방](./asset/bag.jpg)

### 인라인 (inline) 코드 강조
`백티1개`는 `인라인 코드 강조`를 의미한다

```java
  public class Exam{
     public static void main(string[] args){
        system.out.println("exam");
  }
}
```

### 표(table)
|이름|성별|주소|
|:---|:---:|---:|
|신도일|남|서울 서초구|
|홍길동|여|경기도 용인시|

### 인용문(blockQuote)
> 타인의 말이나 문장을 직접 또는 간접으로 가져온다.
>> 인용문1
>>> 인용문2


### 수평선(horizental Rule)
각 기호를 3개 이상 입력하면 된다.
---
(hyphens)
***
(Asterisk)
___
(Underscores)

### 줄바꿈 (line breaks) 
바다<br>
하늘   <--띄어쓰기 2번이상>  
구름   


# TIL

## 리눅스 명령어

1. ls

   > list(목록)

2. cd
   change directory (작업 경로 변경)

3. rm
   remove (파일 삭제)

4. mkdir  
   make directory(작업목록 생성)

5. rmdir  
   remove directory(작업목록 삭제)

6. touch  
   파일생성

7. cat
   파일의 내용 출력

## Git

1. init  
   git 생성
2. add <파일명>  
   staging area로 이동
3. commit -m <메세지>  
   Repository로 이동
4. push <원격저장소><브랜치>  
   원격(GitHub)으로 이동
5. pull <원격저장소><브랜치>  
   원격에서 로컬로 복사
6. clone <원격저장소><브랜치>  
   원격에서 로컬로 복제

7. status  
   Staging Area의 상태
8. log  
   repository의 상태
