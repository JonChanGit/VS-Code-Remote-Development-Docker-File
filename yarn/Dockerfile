FROM node:12.16.3
RUN mkdir -p /home/workerspace
WORKDIR /home/workerspace
RUN npm config set registry https://registry.npm.taobao.org
CMD [ "tail","-f","/dev/null" ]