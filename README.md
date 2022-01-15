# Mysql DB서버를 손쉽게 구축하기 위한 도커파일

## 순서

docker image pull 받기
```
  docker pull mysql:{version}
```

docker image 확인
```
  docker images
```

docker 실행
```
  docker-compose up -d
```

docker 접속
```
docker exec -it {container name} bash
```
