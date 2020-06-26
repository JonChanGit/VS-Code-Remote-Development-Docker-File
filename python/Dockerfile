FROM python:3.8.3
RUN mkdir -p /home/workerspace
WORKDIR /home/workerspace
RUN pip install flake8
RUN pip install yapf
CMD [ "tail","-f","/dev/null" ]