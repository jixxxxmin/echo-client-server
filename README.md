#echo-client, echo-server 프로그램을 제작

- socket 관련 함수를 사용(socket, connect, send, recv, bind, listen, accept 등)

- echo-client(이하 client)는 echo-server(server)에 TCP 접속

- client는 사용자로부터 메세지를 입력받아 server에 메세지를 전달

- server는 받은 메세지를 화면에 출력하고 "-e"(echo) 옵션이 주어진 경우 client에게 메세지를 다시 전송

- server는 "-b"(broadcast) 옵션이 주어진 경우 접속되어 있는 모든 client에게 메세지를 전송

- client는 server로부터 메세지를 받으면 화면에 출력

- server는 여러개 client의 접속 요청 및 데이터 처리 가능해야함(힌트 - thread)
