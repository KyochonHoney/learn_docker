# day 02

도커 명령어

-   docker build
    : 이미지 생성 
    -   docker build 
    -   docker build -t <이미지명:태그> <경로>
    -   docker build . (현재 경로에)

-   docker images
    : 도커 이미지 목록 출력

-   docker run
    : 컨테이너 생성 및 실행
    -   docker run [옵션] <이미지명|ID> [명령어]
    -   docker run -p <호스트 PORT>:<컨테이너 PORT> <이미지명|ID>
    -   docker run -it <이미지명|ID> <명령어>

-   docker ps
    : 실행 중인 컨테이너 목록 출력
    - docker ps -a

-   docker create
    : 컨테이너 생성 ( 실행 별개로 따로 생성하고 싶을 때 )
    -   docker create [옵션] <이미지명|ID> [명령어]

-   docker start
    : 중단된 컨테이너 시작
    -   docker start [옵션] <컨테이너명|ID>

-   docker exec
    : 실행 중인 컨테이너에 접속하여 명령 수행
    -   docker exec [옵션] <컨테이너명|ID> [명령어]

-   docker stop
    : 실행 중인 컨테이너 중단
    -   docker stop [옵션] <컨테이너명|ID>

-   docker pull
    : 레지스트리에 존재하는 도커 이미지 다운
    -   docker pull [옵션] <이미지명>

-   docker rm
    : 도커 컨테이너 삭제
    -   docker rm [옵션] <컨테이너명|ID>

-   docker rmi
    : 도커 이미지 삭제
    -   docker rmi [옵션] <이미지명|ID>

-   docker inspect
    : 도커 이미지 혹은 컨테이너의 자세한 정보 출력
    -   docker inspect [옵션] <이미지 혹은 컨테이너명|ID>



