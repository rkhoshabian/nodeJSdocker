# Use official Node.js 20 Alpine image
FROM node:20-alpine

WORKDIR /app

COPY package*.json ./
COPY index.js ./

EXPOSE 8080

CMD ["node", "index.js"]
