# Base Image
FROM node:alpine
WORKDIR /usr/app

# Dependencies
COPY ./  ./
RUN npm install

# Default command
CMD [ "npm", "start" ]