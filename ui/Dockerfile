FROM node:alpine 

WORKDIR /app

COPY . /app

RUN npm install

EXPOSE 3000

CMD ["API_URL=$API_URL","REACT_APP_NODE_ENV=$REACT_APP_NODE_ENV", "npm", "start"]