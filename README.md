# docker-node.js
A basic node.js application integrated with docker service.

### Getting Started

#### STEP:1 - Build the Docker Container:

```
docker build -t example-node.js .
```

#### STEP:2 - Then run it

```
docker run -p 8080:8080 example-node.js 
```

#### STEP:3 - Now go to localhost:8080 to see the results.

If you make any changes in the code, go to STEP:1 again and build.


