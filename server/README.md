# Server

### Overview

- Local Configuration \* Node Applicaiton
- Dockerization
- Express
- Environment Variables

### Local Configuration

#### Node Application: Packages

- Node v10: A link to stackoverflow how to toggle/install latest node [here](https://stackoverflow.com/questions/8191459/how-do-i-update-node-js)
- NPM v6
- Nodemon
- Express
- Request
- Websockets
- Socket.io

#### Node Application: Dev Dependencies

- Standard
- Snazzy

#### Installation: npm

```bash
npm install
```

### With Docker

> Go back to the parent directory and run following command
> `docker-compose up`

### Without Docker

#### Run locally in browser without Docker

```bash
npm run dev
```

#### Documentation

Using JSDoc

```bash
npm run jsdoc
```

#### Dockerization

Presume Docker is installed. [How to for MacOS](https://docs.docker.com/docker-for-mac/install/)
Docker Container created, source configurable in Dockerfile.

Build the image(s)

```bash
docker image build -t <imagename:tag>
```

Run the image

```bash
docker run -p 9000:9000 <imagename:tag>
```

--- ToDo: Validate these older steps ---

#### Deploying docker image to Heroku

```bash
# Login
heroku login
heroku container:login

# Build and push
heroku container:push web
heroku container:release web
```

- When updating the client app keep in mind you will need to pull the submodule updates from the remote repo before deploying

### Express

- Version 4.16.3
- [Best Practices](https://expressjs.com/en/advanced/best-practice-performance.html)

### Environment Variables

Copy .env.example and save as .env
This is where environment variables will be setup.
