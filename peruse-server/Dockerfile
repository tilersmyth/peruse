FROM node:6

RUN mkdir -p /usr/src/app

WORKDIR /usr/src/app

ADD package.json yarn.lock /usr/src/app/

RUN yarn --pure-lockfile

COPY . /usr/src/app

EXPOSE 4040

CMD ["yarn","start"]