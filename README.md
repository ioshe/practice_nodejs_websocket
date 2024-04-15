![Node.js](https://img.shields.io/badge/node.js-339933.svg?&style=for-the-badge&logo=node.js&logoColor=white)
![Socket.io](https://img.shields.io/badge/socket.io-010101.svg?&style=for-the-badge&logo=socket.io&logoColor=white)
![Express](https://img.shields.io/badge/express-000000.svg?&style=for-the-badge&logo=express&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-E34F26.svg?&style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-1572B6.svg?&style=for-the-badge&logo=css3&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57.svg?&style=for-the-badge&logo=sqlite&logoColor=white)


# Socket.IO 채팅 애플리케이션

이 프로젝트는 Node.js, Express, Socket.IO, 그리고 SQLite를 사용하여 만든 간단한 채팅 애플리케이션입니다. 사용자들은 실시간으로 메시지를 보내고 공유된 텍스트를 실시간으로 편집할 수 있습니다.

## 시작하기

이 애플리케이션을 로컬에서 실행하기 전에 Node.js가 설치되어 있어야 합니다. 필요한 모든 종속성을 설치하려면 다음 명령어를 실행하세요.

```bash
npm install
```

## 데이터베이스 설정
SQLite 데이터베이스 파일을 생성하고 messages 테이블을 초기화합니다. 이 작업은 애플리케이션을 처음 실행할 때 자동으로 처리됩니다.

## 애플리케이션 실행
서버를 시작하려면 다음 명령어를 실행하세요.
```bash
node app.js
```
서버가 시작되면, 브라우저를 열고 http://localhost:3000로 접속하여 애플리케이션을 사용할 수 있습니다.

## 기능
- 메시지 전송: 사용자가 메시지를 입력하고 전송할 수 있습니다.
- 실시간 편집 공유: 사용자가 텍스트를 편집할 때 다른 사용자에게 변경 사항이 실시간으로 반영됩니다.
- 연결 상태 복구: 사용자가 연결이 끊긴 후 재연결할 때 누락된 메시지를 복구할 수 있습니다.
