FROM node:14-alpine

EXPOSE 3001

WORKDIR /back-end

ADD node_modules.tar.gz .

COPY . .

CMD ["npm", "start"]
