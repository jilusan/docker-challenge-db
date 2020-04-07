# Will tell Docker to use the prebuilt NodeJS image
# Alpine based docker Images make a difference in real world Apps
FROM node:13-alpine

# Set the working directory to
WORKDIR /usr/app

# Copu all the files from the project's root to /usr/app
COPY . /usr/app 

# Install node_modules
RUN npm install --quiet

#run commands
CMD ["npm", "start"]
