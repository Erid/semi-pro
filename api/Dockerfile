FROM node:13.3.0
RUN npm install -g --unsafe-perm prisma2

RUN mkdir /app
WORKDIR /app

COPY package*.json ./
COPY prisma ./prisma/

RUN npm install --unsafe-perm
RUN prisma2 generate

CMD [ "npm", "run", "dev" ]
