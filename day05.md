#   day 05

Docker Hub
    : 도커 이미지를 저장하는 저장소 (도커의 공식 레지스트리)

1.  도커 로그인 
    - docker login

2.  도커 빌드
    - docker build -t [사용자]/[레포지토리명]:[TAG] [Dockerfile 경로]

3.  도커 이미지 업로드(push)
    - docker push [사용자]/[레포지토리명]:[TAG]

4.  도커 이미지 저장(pull)
    - docker pull