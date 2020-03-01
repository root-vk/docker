## BASE IMAGE
FROM node:alpine

## WORKING DIRECTORY
WORKDIR '/app'

## INSTALL DEPENDENCIES
COPY package.json .
RUN npm install

## COPY JS FILES
COPY . .

## STARTUP COMMAND
CMD ["npm","start"]
