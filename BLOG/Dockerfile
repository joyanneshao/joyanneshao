# 从dockerhub下载debian镜像
from debian  

# 安装netcat可执行程序和包
run apt-get update
run apt-get -y install netcat  

# 打开80端口
expose 80  

#启动这个容器的时候执行nc命令，监听在80端口上
cmd /bin/nc -l 80
