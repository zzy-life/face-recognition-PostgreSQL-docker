
# 使用docker直接运行
> 基于face-recognition,postgresql数据库制作的人脸识别镜像
> 可以直接拉取使用

拉取镜像

```bash
docker pull registry.cn-hangzhou.aliyuncs.com/zzy_pi/face_postgresql:v1
```

运行命令

```bash
docker run  --env dbhost="数据库ip或域名" --env dbuser="数据库账号" --env dbpassword="数据库密码" -p 5001:5001 face-recognition
```

