FROM node:20.10.0-alpine3.18
WORKDIR /app
COPY --chown=node:node package*.json .
RUN npm install
COPY . .
EXPOSE 8080
USER node
CMD ["node", "server.js"]
