# 通过[Docker](https://docker.io/)运行[TShock](https://github.com/Pryaxis/TShock)，基于[ryansheehan/terraria](https://github.com/ryansheehan/terraria)针对中国大陆网络优化的小版本。
## 具体改动看以下更新日志

## 更新日志
### 2021-09-20
- 修改[tshock/Dockerfile](/tshock/Dockerfile)里的镜像源为[阿里镜像源](https://developer.aliyun.com/mirror/)，加快构建速度。
- 修改启动脚本[tshock/bootstrap.sh](/tshock/bootstrap.sh)，通过[screen](https://wangchujiang.com/linux-command/c/screen.html)实现后台挂起[mono](https://www.mono-project.com/)启动的[Terraria](https://terraria.fandom.com/zh/wiki/Terraria_Wiki)服务器。
- 增加[docker-compose](https://docs.docker.com/compose/)支持。