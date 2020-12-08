# Specify a base image
FROM node:alpine

WORKDIR /usr/app/

# Install some dependencies
COPY ./package.json ./
RUN npm install

# Now it won't install all dependencies
# if we make some changes to the code only
COPY ./ ./


# Default command
CMD ["npm", "start"]
