FROM node:20.14.0-bookworm
# FROM node:lts-bookworm

COPY . /code

WORKDIR /code

RUN yarn install

EXPOSE 9080

CMD ["yarn", "run", "dev"]
