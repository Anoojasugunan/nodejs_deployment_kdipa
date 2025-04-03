FROM node:18.20.8-slim
WORKDIR /app
COPY . .
RUN npm install

USER node
CMD [ "node", "index.js" ]
