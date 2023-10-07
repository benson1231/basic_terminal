# docker  https://www.docker.com/
# docker hub  https://hub.docker.com/
# 教學  https://kawsing.gitbook.io/opensystem/docker-cong-an-zhuang-dao-ying-yong-ru-men-pian/untitled-5
# VS code 資料夾中建立 Dockerfile
```
FROM node:14-alpine
COPY index.js index.js
CMD node / index.js
```
# 創建docker
```
docker build -t (名稱) .
```
# 
```
docker images
```
# 
```
docker run (名稱)
```
# 加上tag(docker-hub-name/repo)
```
docker tag (名稱) (tag)
```
# 上傳
```
docker push (tag) 
```
# 線上  https://labs.play-with-docker.com/
# 拉資料
```
docker pull (tag)
```






