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

<img width="894" alt="Untitled" src="https://user-images.githubusercontent.com/73987960/203698872-63877b86-3c8e-4be0-b50c-ec6ffa3b0734.png">


1. 한 곳에다 몰아주기 위해서 폴더를 만들어준다

<img width="567" alt="Untitled 1" src="https://user-images.githubusercontent.com/73987960/203698879-557da54d-b7a3-4c5f-bb1c-c728e70c00e0.png">

다음과 같이 잘 들어있는 것을 확인할 수 있다

<img width="728" alt="Untitled 2" src="https://user-images.githubusercontent.com/73987960/203698880-c9571b0e-11e8-4aa9-9d63-e50943ad85a1.png">

java -version

<img width="485" alt="Untitled 3" src="https://user-images.githubusercontent.com/73987960/203698881-d7ab4ba1-cdb6-4669-99c3-767974ccb12a.png">

tomcat 9 설치

<img width="946" alt="Untitled 4" src="https://user-images.githubusercontent.com/73987960/203698883-c4b95184-c6fd-4a55-a7dd-28a2c2e00fae.png">

<img width="373" alt="Untitled 5" src="https://user-images.githubusercontent.com/73987960/203698888-68c362dc-b59e-467f-87a6-08a41b605526.png">

<img width="369" alt="Untitled 6" src="https://user-images.githubusercontent.com/73987960/203698891-d2e995f4-1419-4749-879c-624ff5fb5cd2.png">

tomcat9 폴더를 만들어준다

<img width="372" alt="Untitled 7" src="https://user-images.githubusercontent.com/73987960/203698893-d260748a-92f1-46e2-b3a8-c56456af4053.png">

<img width="242" alt="Untitled 8" src="https://user-images.githubusercontent.com/73987960/203698895-fa178bed-7362-41da-a77f-28acc946da81.png">

<img width="305" alt="Untitled 9" src="https://user-images.githubusercontent.com/73987960/203698897-a20e0fc2-373d-420b-8993-ad7cdfc6e9f7.png">

[http://127.0.0.1:8080/](http://127.0.0.1:8080/) → tomcat이 잘 실행되고 있음을 확인 할 수 있다

<img width="956" alt="Untitled 10" src="https://user-images.githubusercontent.com/73987960/203698899-16fd8d8b-5b5d-4a80-bc88-8b5d767c8a58.png">

ipconfg 

(drag 엔터 누르면 복사가 된다)

<img width="590" alt="Untitled 11" src="https://user-images.githubusercontent.com/73987960/203698903-e60de207-5e9f-4f02-b9c8-a4144a5be39a.png">

[http://176.16.1.33:8080/](http://176.16.1.33:8080/)

<img width="947" alt="Untitled 12" src="https://user-images.githubusercontent.com/73987960/203698905-3b94d148-6533-41ea-8873-f37677c2cc4d.png">

<img width="839" alt="Untitled 13" src="https://user-images.githubusercontent.com/73987960/203698908-5ccea957-6bf2-4177-83ed-3c4ec98864f8.png">

<img width="832" alt="Untitled 14" src="https://user-images.githubusercontent.com/73987960/203698910-d496ca18-5e3d-4d78-a6f7-1637e71c61b7.png">

친구 컴퓨터에 잘들어가지는 것을 확인할 수 있다

<img width="952" alt="Untitled 15" src="https://user-images.githubusercontent.com/73987960/203698911-e6e10fcd-9689-4aaf-b0cf-e279a97671c5.png">

eclipse 설치

<img width="357" alt="Untitled 16" src="https://user-images.githubusercontent.com/73987960/203698915-812ea168-66bb-49e3-baa0-bdc55700906b.png">

<img width="656" alt="Untitled 17" src="https://user-images.githubusercontent.com/73987960/203698917-17632be9-426e-4353-be9f-bb34b563cc71.png">

sba 밑에 worksapce를 만든다 (모든 파일이 여기에 모인다)

<img width="420" alt="Untitled 18" src="https://user-images.githubusercontent.com/73987960/203698918-051e8ba5-77eb-482c-9866-5def307c5a34.png">

<img width="960" alt="Untitled 19" src="https://user-images.githubusercontent.com/73987960/203698920-33d21507-e37e-4995-9208-701c9e39b5ba.png">

<img width="830" alt="Untitled 20" src="https://user-images.githubusercontent.com/73987960/203698922-2d5c2319-d9f7-4a6c-89a2-2b860100453d.png">

<img width="340" alt="Untitled 21" src="https://user-images.githubusercontent.com/73987960/203698924-7d20a83c-b397-4401-8bf4-055f00de8457.png">

<img width="959" alt="Untitled 22" src="https://user-images.githubusercontent.com/73987960/203698927-49ed0499-1e80-4d96-a526-6910868c3d60.png">

<img width="364" alt="Untitled 23" src="https://user-images.githubusercontent.com/73987960/203698928-b86d85b3-e2f7-4282-b305-1721455c2ccf.png">

<img width="383" alt="Untitled 24" src="https://user-images.githubusercontent.com/73987960/203698930-e11eca2b-b78d-4ae5-96f7-37d1ecfbe887.png">

<img width="960" alt="Untitled 25" src="https://user-images.githubusercontent.com/73987960/203698933-c7a8b94d-b47c-46e0-856c-30c9612d30ba.png">

<img width="956" alt="Untitled 26" src="https://user-images.githubusercontent.com/73987960/203698935-3fd1a713-f925-4570-93ce-1e2da478d49c.png">

<img width="932" alt="Untitled 27" src="https://user-images.githubusercontent.com/73987960/203698937-fa5b41c0-85c5-40f9-9b2d-88f30f0a53ad.png">

<img width="306" alt="Untitled 28" src="https://user-images.githubusercontent.com/73987960/203698939-c5414b44-4a5c-4aee-83be-a2a2c651ae28.png">

숨겨진 아이콘에 가서 stop을 눌러준다

( eclipse에서만 사용하면 되기 때문에)

<img width="638" alt="Untitled 29" src="https://user-images.githubusercontent.com/73987960/203698940-f741b11f-c268-4edd-b3df-97d68e7c950e.png">

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

<img width="718" alt="Untitled 30" src="https://user-images.githubusercontent.com/73987960/203698944-da2f8ee3-6fc3-4277-9d11-489fabda4dde.png">

encoding **UTF-8**로 바꿔준다

<img width="896" alt="Untitled 31" src="https://user-images.githubusercontent.com/73987960/203698946-da5b9359-c52a-42e6-adf0-5b406d3529e6.png">

<img width="892" alt="Untitled 32" src="https://user-images.githubusercontent.com/73987960/203698947-7fd24513-e244-44c3-a222-8ad85aad61c7.png">

<img width="894" alt="Untitled 33" src="https://user-images.githubusercontent.com/73987960/203698948-d5a3760c-788d-45db-9770-c96e78b6f8c6.png">

<img width="957" alt="Untitled 34" src="https://user-images.githubusercontent.com/73987960/203698954-0334ca96-1266-48a6-a413-2284dda00b40.png">

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