FROM node
#LABEL maintainer="Sidney Rodrigues"
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 8080
CMD ["node", "server.js"]