FROM node:14

WORKDIR /app

COPY server.js .
COPY index.html .
COPY images ./images 
COPY package.json .

RUN npm i

EXPOSE 3000

CMD ["node", "server.js"]
