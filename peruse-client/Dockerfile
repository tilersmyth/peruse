FROM node:6.10.2-alpine

RUN mkdir -p /app

WORKDIR /app

COPY package.json /app/

RUN ["npm", "install"]

COPY . /app

EXPOSE 3000/tcp

CMD ["npm", "run", "start:docker"]