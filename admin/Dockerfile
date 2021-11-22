FROM node:14-alpine

WORKDIR /usr/src/admin

COPY . /usr/src/admin

RUN npm ci
RUN npm run build

# EXPOSE 3000


CMD ["npm", "run", "start"]