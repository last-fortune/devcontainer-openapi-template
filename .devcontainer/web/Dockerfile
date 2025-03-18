FROM node:22.14
# openapi-generator-cliを動かすためにjavaが必要
RUN apt update; apt install -y wget software-properties-common apt-transport-https git openjdk-17-jre
RUN npm install -g yml-sorter redoc redoc-cli @openapitools/openapi-generator-cli version-manager
# redocly-cliをインストール(ほかと分けたほうが良さそう)
RUN npm install -g @redocly/cli
# firebase に deployするため
RUN npm install -g firebase-tools