# centos-lamp
한번에 CentOS 7 에  AMP + OpenSSL  설치 하기.

본인이 사용하기 쉽게 만든 파일로 centos7 에서만 사용해보았습니다.\
centOS 기타 버전이나 rockyOS 에서는 테스트 해보지 않았습니다.


## 설치 방법

### AMP 설치
$ ./vhost.sh install

### 가상서버 관리

$ ./vhost.sh add   // 새 가상서버 추가 

$ ./vhost.sh del   // 생성된 가상서버 삭제  

$ ./vhost.sh list   // 생성된 가상서버 목록조회
 

## 참고 소스

https://lamp.sh
