FROM node:14-alpine
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app
COPY package.json /usr/src/app
RUN npm i
COPY . /usr/src/app
CMD ["npm", "start"]
