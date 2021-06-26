# Docker Node MongoDB Example

> Simple example of a Dockerized Node/Mongo app 🐳 👍

## Get Started

To install and run the example, first clone the repository and optionally replace the "dockerExample" directory with your desired name.

```bash
git clone https://github.com/greatdane89/docker-node-mongo-example.git dockerExample
```

Next, run the following commands in your CLI to navigate into the proper directory, install the dependencies and start the server. Remember to replace the "dockerExample" directory with your desired name.

```bash
#Navigate into proper directory
cd dockerExample

#install dependencies
npm install

#Run the application
npm run start

```

Visit http://localhost:3000 in your browser.

## Commands

```bash
# Run in Docker
docker-compose up
# use -d flag to run in background

# Tear down
docker-compose down

# To be able to edit files, add volume to compose file
volumes: ['./:/usr/src/app']

# To re-build
docker-compose build
```
