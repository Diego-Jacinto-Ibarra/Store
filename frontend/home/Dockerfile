FROM node:20.15

WORKDIR /app

COPY frontend/home ./

RUN npm install

CMD ["npm", "run", "dev", "--", "-p", "10000"]
