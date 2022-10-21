# Latest LTS Node release as of 2022.10.19
FROM node:16.18.0-alpine3.16

# Set working directory for image
WORKDIR /app

# Copy package.json and yarn.lock to root directory
<<<<<<< HEAD
#COPY /app/package*.json ./
=======
COPY /app/package*.json ./
>>>>>>> e37e1d0e6c9f0848eafb6c407aedfb8b7b9aed64

# Install all necessary packages
RUN npm install

#ENV PATH=$PATH:./node_modules/.bin

COPY /app .