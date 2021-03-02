# Base repository to NodeJS projects using typescript.

## How to use

Once you installed docker and configured your own Dockerfile (you can use my configurations instead). You should follow the steps to run the application (inside of this repository folder on your machine):

```terminal
docker build --tag <dockerName>
docker run -d -p <ServerPort>:<NodePort> <dockerName>
```

If you want more information about docker you can access: https://www.docker.com/blog/getting-started-with-docker-using-node-jspart-i/.
