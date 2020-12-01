# Capstone-sodam


![소담 아이콘](https://user-images.githubusercontent.com/63000843/99904801-aff92700-2d10-11eb-9cd3-b9606e8f71c3.png)

# 사용방법
1) npm i 를 터미널에서 실행하여 npm 들을 설치해줍니다.
2) DB와 연동하기 위하여 .env에 다음과 같이 입력합니다.

```
DB_HOST = "호스트"
DB_USER = "계정"
DB_PASSWORD = "비밀번호"
DB_DATABASE = "스키마"
COOKIE_SECRET = ""
```
3) config 폴더를 만들어 awsconfig.json을 다음과 같이 입력합니다. 꼭 .gitignore 처리를 해주세요.

```
{
    "accessKeyId": "aws accesskey를 넣어주세요.",
    "secretAccessKey": "aws accesskey를 넣어주세요.",
    "region": "ap-northeast-2" //본인 지역을 넣어주세요. 
  }
```
4) npm start을 터미널에 입력하여 실행시켜줍니다.


# 내역
###
* 터미널을 열어 npm i 명령어로 실행에 필요한 npm 들을 설치해줍니다.
* 설치한 후 npm i -D nodemon 명령어로 developer시에 nodemon을 사용할 수 있게 설치해줍니다.
* 다 하셨으면 npm start 로 시작후 브라우저에서 localhost:3000 으로 맵핑하면 됩니다.

### 
* 서버디비와 연결
* Node.js와 Mysql 연동
* DB connection 모듈화
* DB 정보 env에 담아서 외부에 노출 되지 않게함.
* gitignore로 env 무시

