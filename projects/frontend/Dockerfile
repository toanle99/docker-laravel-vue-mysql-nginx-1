FROM node:16.19.0

WORKDIR /var/www/html/proje

COPY package*.json ./

RUN npm install


CMD ["npm", "run", "build"]