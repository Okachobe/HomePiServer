# Name the node stage "builder"
FROM node:10 AS builder

# Set working directory
WORKDIR /app

# Copy all files from current directory to working dur in image
COPY . .

# Install node modules and build assets

RUN yarn install && yarn build