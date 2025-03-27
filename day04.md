# day 04

Dockerfile 명령어

-   FROM 이미지:태그
    : 생성할 이미지의 기반이 되는 base 이미지 지정.

-   ENV 변수명 값 
    : 환경 변수 지정

-   RUN
    : 이미지 빌드할 때 실행할 명령어 작성
    -   RUN apt-get update
    -   RUN ["/bin/bash", "-c", "echo hello"]

-   COPY
    : src 파일이나 디렉토리를 이미지 파일 시스템의 dest로 복사
    -   COPY <src> <dest>

-   ADD
    : src 파일이나 디렉토리, URL 이미지 파일 시스템의 dest로 복사
    -   ADD <src> <dest>

-   WORKDIR
    : Dockerfile 내의 명령을 수행할 작업 디렉토리를 지정
    -   WORKDIR /home/user

-   USER
    : 명령을 수행할 사용자 혹은 그룹 지정
    -   USER $username

-   EXPOSE
    : 포트 및 프로토콜 지정
    -   EXPOSE 80/tcp

-   ENTRYPOINT
    : 컨테이너가 실행될 때 수행할 명령어 지정
    -   ENTRYPOINT ["echo", "hello"]

-   CMD
    : 수행할 명령어를 지정
    -   CMD ["echo", "hello"]
    

