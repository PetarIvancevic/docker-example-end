FROM node:6.7

RUN useradd --user-group --create-home --shell /bin/bash app

RUN mkdir /home/app/src

COPY . /home/app/src

WORKDIR /home/app/src
