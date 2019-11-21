FROM node

WORKDIR /app/

# Use intially created package files to install dependencies
COPY package.json yarn.lock /app/

RUN npm install
