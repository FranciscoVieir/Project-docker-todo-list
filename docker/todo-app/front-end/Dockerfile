FROM node:14-alpine

WORKDIR /app

EXPOSE 3000

COPY . .
RUN npm install


ADD node_modules.tar.gz .

CMD ["npm", "start"]