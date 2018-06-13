# 메신져 채팅용 웹 소켓 서버

## 실행
```bash
# 라이브러리 인스톨(처음에 한번만 해주면 됨)
> npm i
# 실행
> npm start
```

## 웹 소켓 설정
- 개발용 내부포털 소스의 웹소켓 접속 주소를 현재 웹소켓 서버가 실행되고 있는 주소로 변경해줘야 함
- 진흥원 내부에서는 개발서버에 띄워놓고 있음. 아래 부분의 주소와 포트를 수정하면 됨
```javascript
var socket =  io.connect('http://10.1.10.15:9091');
```
