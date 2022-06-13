FROM node:16-alpine

WORKDIR /app

COPY ./package* ./
RUN npm ci --production

COPY ./*.js ./

EXPOSE 3000
CMD ["node", "index.js"]
