FROM node:14

# Create application directory
WORKDIR /usr/src/app

# Install application dependencies
COPY package*.json ./
RUN npm install

# Copy application source code
COPY . .

# The port the application binds to
EXPOSE 8080

CMD [ "node", "server.js" ]
