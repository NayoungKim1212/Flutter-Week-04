# Flutter-Week-04 API 사용법 익히기
 
## 동기 & 비동기

### 1. 동기
- 하나의 일이 끝난 뒤 다음 일을 하는 방식
  -  HTTP 요청을 보낸 뒤 응답 받은 결과를 보여주는 코드를 작성할 때
     - 비동기 방식으로 동작하는 경우, 응답을 받기 전에 결과를 보여주려고 하며 에러가 발생하기 때문에 
### 2. 비동기
- 하나의 일이 끝나기 전에 동시에 다른 일을 하는 방식
- 오래 걸리는 작업을 처리할 때 유용
  -  네트워크 요청, 데이터베이스 접근
### 즉, 요청을 보내기만 하면 되는 코드의 경우 비동기 방식으로 처리하고 요청에 대한 응답을 받아서 보여줘야 하는 코드는 동기 방식으로 처리
