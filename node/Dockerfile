FROM node

ENV NODE_ENV=DEVELOPMENT

# オプションで -g を付けないとエラー発生
RUN npm install -g express@4.18.1

WORKDIR /tea-database-api

# Dockerfileのportsのコロン(:)挟んだ右側の数値と合わせる
EXPOSE 8000