FROM node:14-alpine

WORKDIR /usr/src/webmaster

COPY . /usr/src/webmaster

RUN npm ci
RUN npm run build

# EXPOSE 3000


CMD ["npm", "run", "start"]