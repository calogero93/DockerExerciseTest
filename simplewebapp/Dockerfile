# Specify a base image
FROM node:alpine


# Install some dependecies
COPY ./package.json ./
RUN npm install
COPY ./ ./

# Default command
CMD ["npm","start"]