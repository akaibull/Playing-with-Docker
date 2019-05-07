FROM ubuntu
RUN apt-get update && apt install -y curl && apt-get clean && rm -rf /var/lib/apt/list/* 

RUN mkdir /home/Codes

ENV USER test1
ENV SHELL /bin/bash
ENV LOGNAME mani 

CMD ["bash"]
