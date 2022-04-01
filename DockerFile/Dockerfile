FROM httpd
# 指定基础镜像httpd（web服务）
MAINTAINER MengZhiRong
# 作者
COPY Web-Site /
# 把主机文件复制到容器目录
WORKDIR /
# 工作目录（进入容器时的目录）
EXPOSE 8080
# 暴露端口
CMD [/bin/bash]