FROM nginx
# 指定基础镜像httpd（web服务）
MAINTAINER MengZhiRong
# 作者
COPY /Web-Site /usr/share/nginx/html
# 把主机文件复制到容器目录
WORKDIR /usr/share/nginx/html
# 工作目录（进入容器时的目录）
EXPOSE 80
# 暴露端口
CMD [/bin/bash]