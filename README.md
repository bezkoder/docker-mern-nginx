# Docker Compose MERN Stack with Nginx example

Dockerize fullstack: React, Nodejs Express and MongoDB (MERN stack application) example using Docker Compose with Nginx.

## Run the System
We can easily run the whole with only a single command:
```bash
docker-compose up
```

Docker will pull the MongoDB and Node.js images (if our machine does not have it before).

The services can be run on the background with command:
```bash
docker-compose up -d
```

## Stop the System
Stopping all the running containers is also simple with a single command:
```bash
docker-compose down
```

If you need to stop and remove all containers, networks, and all images used by any service in <em>docker-compose.yml</em> file, use the command:
```bash
docker-compose down --rmi all
```

For more detail, please visit:
> [Docker Compose MERN Stack with Nginx example](https://www.bezkoder.com/docker-mern/)

Related Posts:
> [React + Node.js + Express + MongoDB example](https://bezkoder.com/react-node-express-mongodb-mern-stack/)

> [React + Node.js Express + MongoDB: User Authentication with JWT example](https://www.bezkoder.com/react-node-mongodb-auth/)

Integration (run back-end & front-end on same server/port)
> [Integrate React with Node.js Restful Services](https://bezkoder.com/integrate-react-express-same-server-port/)