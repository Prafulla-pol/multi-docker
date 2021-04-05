FROM node:10.24.0-alpine
WORKDIR '/app'
COPY ./package*.json ./
RUN npm install
COPY . .
CMD ["npm", "run", "start"]