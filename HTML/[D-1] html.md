# [D-1] 22.11.23

### 설치 항목

**jdk+tomcat+eclipse(인텔리제이)+chrome**

## 웹 개발이란

웹 = 인터넷 사용 컴퓨터 네트워킹

네트워크 - 여러대 컴퓨터 접속 가능

내컴퓨터 접속 기능 사용자 

| 내컴퓨터 = 서버 컴퓨터 | 내컴퓨터 접속 기능 사용 컴퓨터 = 클라이언트 컴퓨터 |
| --- | --- |
| 하드웨어
소프트웨어
네트워크 언어 = protocol
웹 서비스 = http protocol
iis, apache, tomcat | 웹 브라우저 = 웹 클라이언트  |

| 프론트엔드 | 백엔드 |
| --- | --- |
| 홈페이지 기업 홍보
로그인 내정보 확인 | 데이터베이스
데이터베이스 연결 정보 조회 / 추가 / 수정 / 삭제 → 자바, servlet, jsp, spring |

| 웹서버 | 웹 클라이언트 |
| --- | --- |
| 백엔드 - 자바 작성 실행
프론트 -  html / css / js 작성 실행
jdk - C:\sba\jdk17
tomcat - 웹 서버
eclipse - it 소스파일 편집기
IDE - INTEGRATEDE
jdk - 자바 프로그램 실행
(tomcat, eclipse 먼저 설치 필수)
tomcat - html ~  jsp 프로그램 실행 | 크롬
http://127.0.0.1:8080 |

| eclipse 내부 c:/sba/workspace |
| --- |
| html / css / js → 웹 프론트엔드 파일 저장 프로젝트 - dynamic web project
html 확장자 파일 →c:/sba/workspace./html(프로젝트이름)/src/main/webapp
(자바 → java project)
(spring → spring mvc project / spring boot) |
|  |

### 환경 설정

1. Chrome 설치
2. java 17 설치 (exe)

<img width="567" alt="Untitled 1" src="https://user-images.githubusercontent.com/73987960/203691910-d4a57dba-59dc-4a7c-bbb9-e7a1ea230753.png">


1. 한 곳에다 몰아주기 위해서 폴더를 만들어준다

![Untitled](%5BD-1%5D%2022%2011%2023%2011d54ed6f50f49eabd35455356800b7e/Untitled%201.png)

다음과 같이 잘 들어있는 것을 확인할 수 있다

![Untitled](%5BD-1%5D%2022%2011%2023%2011d54ed6f50f49eabd35455356800b7e/Untitled%202.png)

java -version

![Untitled](%5BD-1%5D%2022%2011%2023%2011d54ed6f50f49eabd35455356800b7e/Untitled%203.png)

tomcat 9 설치

![Untitled](%5BD-1%5D%2022%2011%2023%2011d54ed6f50f49eabd35455356800b7e/Untitled%204.png)

![Untitled](%5BD-1%5D%2022%2011%2023%2011d54ed6f50f49eabd35455356800b7e/Untitled%205.png)

![Untitled](%5BD-1%5D%2022%2011%2023%2011d54ed6f50f49eabd35455356800b7e/Untitled%206.png)

tomcat9 폴더를 만들어준다

![Untitled](%5BD-1%5D%2022%2011%2023%2011d54ed6f50f49eabd35455356800b7e/Untitled%207.png)

![Untitled](%5BD-1%5D%2022%2011%2023%2011d54ed6f50f49eabd35455356800b7e/Untitled%208.png)

![Untitled](%5BD-1%5D%2022%2011%2023%2011d54ed6f50f49eabd35455356800b7e/Untitled%209.png)

[http://127.0.0.1:8080/](http://127.0.0.1:8080/) → tomcat이 잘 실행되고 있음을 확인 할 수 있다

![Untitled](%5BD-1%5D%2022%2011%2023%2011d54ed6f50f49eabd35455356800b7e/Untitled%2010.png)

ipconfg 

(drag 엔터 누르면 복사가 된다)

![Untitled](%5BD-1%5D%2022%2011%2023%2011d54ed6f50f49eabd35455356800b7e/Untitled%2011.png)

[http://176.16.1.33:8080/](http://176.16.1.33:8080/)

![Untitled](%5BD-1%5D%2022%2011%2023%2011d54ed6f50f49eabd35455356800b7e/Untitled%2012.png)

![Untitled](%5BD-1%5D%2022%2011%2023%2011d54ed6f50f49eabd35455356800b7e/Untitled%2013.png)

![Untitled](%5BD-1%5D%2022%2011%2023%2011d54ed6f50f49eabd35455356800b7e/Untitled%2014.png)

친구 컴퓨터에 잘들어가지는 것을 확인할 수 있다

![Untitled](%5BD-1%5D%2022%2011%2023%2011d54ed6f50f49eabd35455356800b7e/Untitled%2015.png)

eclipse 설치

![Untitled](%5BD-1%5D%2022%2011%2023%2011d54ed6f50f49eabd35455356800b7e/Untitled%2016.png)

![Untitled](%5BD-1%5D%2022%2011%2023%2011d54ed6f50f49eabd35455356800b7e/Untitled%2017.png)

sba 밑에 worksapce를 만든다 (모든 파일이 여기에 모인다)

![Untitled](%5BD-1%5D%2022%2011%2023%2011d54ed6f50f49eabd35455356800b7e/Untitled%2018.png)

![Untitled](%5BD-1%5D%2022%2011%2023%2011d54ed6f50f49eabd35455356800b7e/Untitled%2019.png)

![Untitled](%5BD-1%5D%2022%2011%2023%2011d54ed6f50f49eabd35455356800b7e/Untitled%2020.png)

![Untitled](%5BD-1%5D%2022%2011%2023%2011d54ed6f50f49eabd35455356800b7e/Untitled%2021.png)

![Untitled](%5BD-1%5D%2022%2011%2023%2011d54ed6f50f49eabd35455356800b7e/Untitled%2022.png)

![Untitled](%5BD-1%5D%2022%2011%2023%2011d54ed6f50f49eabd35455356800b7e/Untitled%2023.png)

![Untitled](%5BD-1%5D%2022%2011%2023%2011d54ed6f50f49eabd35455356800b7e/Untitled%2024.png)

![Untitled](%5BD-1%5D%2022%2011%2023%2011d54ed6f50f49eabd35455356800b7e/Untitled%2025.png)

![Untitled](%5BD-1%5D%2022%2011%2023%2011d54ed6f50f49eabd35455356800b7e/Untitled%2026.png)

![Untitled](%5BD-1%5D%2022%2011%2023%2011d54ed6f50f49eabd35455356800b7e/Untitled%2027.png)

![Untitled](%5BD-1%5D%2022%2011%2023%2011d54ed6f50f49eabd35455356800b7e/Untitled%2028.png)

숨겨진 아이콘에 가서 stop을 눌러준다

( eclipse에서만 사용하면 되기 때문에)

![Untitled](%5BD-1%5D%2022%2011%2023%2011d54ed6f50f49eabd35455356800b7e/Untitled%2029.png)

```html
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>EPL</title>
</head>
<body>
<h1>Arsenal</h1>
</body>
</html>
```

```html
<body>
1. 대소문자 구분 하지 않는다
2. 이클립스 ide - dynamic web project - src/main/webapp
3. run as - run on server - 브라우저 자동 실행
4. http://127.0.0.1:8080/html/first.html 자동 주소 입력
5. url -> 프로토콜명(http) : // ip:port/경로/파일명
127.0.0.1 - 내컴퓨터 / port  - 서버프로그램 식별번호 (중복이 되면 안된다) / tomcat - 설치시 8080

</body>
```

start stop을 할 수 있다

![Untitled](%5BD-1%5D%2022%2011%2023%2011d54ed6f50f49eabd35455356800b7e/Untitled%2030.png)

encoding **UTF-8**로 바꿔준다

![Untitled](%5BD-1%5D%2022%2011%2023%2011d54ed6f50f49eabd35455356800b7e/Untitled%2031.png)

![Untitled](%5BD-1%5D%2022%2011%2023%2011d54ed6f50f49eabd35455356800b7e/Untitled%2032.png)

![Untitled](%5BD-1%5D%2022%2011%2023%2011d54ed6f50f49eabd35455356800b7e/Untitled%2033.png)

![Untitled](%5BD-1%5D%2022%2011%2023%2011d54ed6f50f49eabd35455356800b7e/Untitled%2034.png)

---

서버 VS 클라이언트

### 클라이언트

- 사용자가 웹 사이트에 접근할 떄 사용하는 기기
- (좁은 의미) 웹 브라우저

### 서버

- 인터넷에 연결된 컴퓨터
- 웹 요소와 여러 정보가 저장됨

### 프론트엔드

- 웹 브라우저 화면에 보이는 부분을 다룸 → 웹 사이트 제작
- HTML, CSS, 자바스크립트 사용

### 백엔드

- 사용자 뒤(back)에서 보이지 않는 영역, 즉 서버를 다룸
- 데이터베이스를 설계하거나 데이터 처리
- 자바, PHP, Python 등 프로그래밍 언어 사용

---

## 웹 개발의 기본

HTML : 웹 문서의 뼈대를 만드는 것

- 웹 브라우저 창에 웹 문서의 내용을 보여주기 위한