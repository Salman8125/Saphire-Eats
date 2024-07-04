FROM node:20.12.2

WORKDIR /usr/src/app

COPY . .

RUN npm install 

CMD ["npm", "run", "dev", "--", "--host"]