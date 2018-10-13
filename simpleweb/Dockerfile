FROM node:alpine

ENV WORKDIR="/app"
WORKDIR $WORKDIR 

COPY package.json ./ 
RUN npm install

COPY . ./ 

CMD ["npm", "start"]
