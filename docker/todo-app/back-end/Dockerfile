FROM node:14-alpine

WORKDIR /app

EXPOSE 3001

COPY . .
RUN npm install


ADD node_modules.tar.gz .

CMD ["npm", "start"]