# 네트워크 오목게임
출처 : https://blog.anyjava.net/108

소스 출처 : https://github.com/anyjava/FiveStonesGame

네트워크 모옥게임으로서 1:1 대전기능 및 채팅/쪽지 기능이 있는 오목게임 서버 &amp; 클라이언트 입니다.

## 필요환경
- JDK 1.5 이상 설치    
   [JDK 다운로드](http://www.oracle.com/technetwork/java/javase/downloads/index.html)

## 설치방법
- project_FiveStoneGame.jar 파일 다운로드
- 위 파일을 동일폴더에 위치 시키고 실행한다.

## 실행방법
- 다운받은 jar 파일을 실행시킨다. (cmd창에 경로 파일에서)
  `java -jar project_FiveStoneGame.jar`
- 혹은 미리 만들어놓은 start.bat 파일을 실행

- 아이디 비번은 아무거나 입력 (회원가입 기능 없음)

![오목 로그인](http://img.anyjava.net/upload/omock/0004.jpg)

- 대기실

![대기실](http://img.anyjava.net/upload/omock/0001.jpg)

- 게임 대기실

![게임 대기실](http://img.anyjava.net/upload/omock/0002.jpg)

- 게임화면

![게임화면](http://img.anyjava.net/upload/omock/0003.jpg)


========================================================================

## 힘들었던 점
- jar 파일을 실행파일로 실행했을 경우 이미지 파일이 다 날라갔음
- 이럴 경우 방법은 두 가지인데 이미지 폴더안에 있는 이미지를 전부 패키지에 넣거나,
- 이클립스안에서 프로젝트 옵션에서 소스 폴더를 수정한 후 export하기
- (Ex) 소스 폴더 수정) 프로젝트 우클릭 -> properies (옵션) -> java build path -> source -> add folder
   -> image 체크하기 -> image 파일 더블클릭 후 next -> exclusion patterns ->
   add multple.. -> 싹다 긁어서 ok -> finish
- (Ex) export) 프로젝트 우클릭 -> export -> java -> Runnable JAR file
 -> Launch configuration(clientLobby (실행하는 파일을 잡으면 됨))
 -> Export destination(만들어 놓은 .jar파일 경로 설정)
 -> finish

## 아쉬웠던 점
- 좀 더 옵션 추가를 넣지 못했던 것
- (Ex1) 첫 시작하는 사람이 무조건 검은색 돌로 시작.
- (EX2) 첫 시작하는 검은색 돌은 오목 규칙인 33룰 옵션을 넣지 못한 것.
