FROM node:18-alpine

WORKDIR /var/www/html
COPY ./front /var/www/html

RUN npm install

EXPOSE 3000

CMD ["npm", "run", "start"]
