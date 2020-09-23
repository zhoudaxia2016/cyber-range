FROM vulnerables/web-dvwa
RUN echo " " > /etc/apt/sources.list
RUN echo "deb http://mirrors.aliyun.com/debian jessie main" >> /etc/apt/sources.list
RUN echo "deb http://mirrors.aliyun.com/debian jessie-updates main" >> /etc/apt/sources.list
RUN apt update -y
RUN apt install vim -y
