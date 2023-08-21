FROM node:16.20.2

LABEL maintainer="tech@appsmith.com"

WORKDIR /app

COPY package.json dist ./

EXPOSE 8091

CMD ["node", "--require", "source-map-support/register", "server.js"]
