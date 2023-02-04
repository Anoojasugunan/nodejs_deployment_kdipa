FROM node:18.0-slim
WORKDIR /app
COPY . .
RUN npm install

USER node
CMD [ "node", "index.js" ]
