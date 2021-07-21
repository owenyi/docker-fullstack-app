FROM node:12-alpine

WORKDIR /app

COPY ./packge.json ./

RUN yarn install

COPY ./ ./

CMD ["yarn", "run", "start"]