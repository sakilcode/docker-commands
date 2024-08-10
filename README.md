### Spin up a NodeJS Docker Container for Development
```sh
docker run --rm -it -p 3000:3000 -v $(pwd):/app -w /app --name <PROJECT_NAME> node:20-alpine s
```
