FROM alpine

RUN apk add --update npm

WORKDIR sipleweb

COPY package.json ./package.json

RUN npm isntall

COPY index.js ./index.js

EXPOSE 8080

CMD ["npm", "start"]