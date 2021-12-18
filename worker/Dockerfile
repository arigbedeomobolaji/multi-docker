FROM node:alpine
WORKDIR '/app'
RUN npm install -g npm@8.1.4
COPY package.json .
RUN npm install
COPY . .
CMD ["npm", "run", "start"]