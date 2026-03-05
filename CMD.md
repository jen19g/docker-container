# VSCode connect to container of docker

## ① 確保 container 正在跑
### Windows
```sh
docker compose up -d
```

## ② 在 VSCode 按
### Windows
```sh
Ctrl + Shift + P

"輸入指令"
Dev Containers: Attach to Running Container
```

## ③ 選container

# docker image build
# 在專案根目錄 build
### Windows
```sh
docker build -f Dockerfile.prod -t {image_name}:{version} .
# docker build -f Dockerfile.prod -t my-jesse-bot:latest .
```

# docker image run
# 啟動 production
### Windows
```sh
docker compose -f {docker-compose.pro.yml} up -d
#docker compose -f docker/docker-compose.prod.yml up -d
```
