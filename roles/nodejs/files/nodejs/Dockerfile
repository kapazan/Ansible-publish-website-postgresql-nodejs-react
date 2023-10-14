FROM node:14

# create app directory
WORKDIR /usr/src/app

# package*.json will be copied to "WORKDIR" PATH
COPY package*.json ./       

RUN npm install

COPY . .

EXPOSE 5000

CMD ["node","app.js"]