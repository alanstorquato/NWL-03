FROM node:12.19.0

WORKDIR /app

COPY package.json /app

RUN yarn install

COPY . /app

CMD ["yarn", "dev"]


# yarn add @types/express -D

# yarn add typescript -D

# yarn add typeorm
