# STOMP 소켓 서버 도커로 실행하기

### 서버 도커 이미지 파일 다운로드
https://drive.google.com/file/d/1xl50s7KH8rVVJCSaDxXuCfJjs6yspd4w/view?usp=sharing

### 서버 실행하기

```shell
docker load -i spring-stomp-docker.tar

docker images


docker run --tty -p 8080:8080 spring-stomp-docker:0.0.1-SNAPSHOT

# 백그라운드
docker run -d -p 8080:8080 spring-stomp-docker:0.0.1-SNAPSHOT
```