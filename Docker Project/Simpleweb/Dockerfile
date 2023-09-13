#Specify a base image
FROM node:18-alpine
#Create an working directory
WORKDIR /usr/app
#copy the app files into working directory
COPY ./ ./
#download and install dependency
RUN npm install 
#tell the image to run the command
CMD ["npm","start"]