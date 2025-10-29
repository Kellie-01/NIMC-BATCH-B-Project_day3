FROM node:18-alpine

WORKDIR /app
#copy dependencies
COPY package*.json ./
#run installation
RUN npm install
#copy the remaining programm files to the container
COPY . .
#expose the port
EXPOSE 5000
#run the backend application- this is on node JS
CMD [ "node", "server.js" ]
