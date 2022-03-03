# rocketchat-arm

## 使用现成的镜像
```bash
docker pull jxch/rocketchat-arm

# docker-compose.yml 文件中
    images:rocketchat:4.1.2 改为 images:jxch/rocketchat-arm
    并且把 ROOT_URL 改成自己的域名
docker-compose up -d
```

## 自行构建镜像
```bash
docker build -t rocketchat:4.1.2 .

# docker-compose.yml 文件中 ROOT_URL 改成自己的域名
docker-compose up -d
```
