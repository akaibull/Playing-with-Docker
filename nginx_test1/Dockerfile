FROM ubuntu:16.04
RUN apt-get update && apt install -y nginx && apt-get clean && rm -rf /var/lib/apt/list/* 

EXPOSE 80

CMD ["nginx","-g","daemon off;"]
