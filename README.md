### Spin up a NodeJS Docker Container for Development
```sh
docker run --rm -it -p 3000:3000 -v $(pwd):/app -w /app --name project_name node:20-alpine sh

# Update npm version
npm i -g npm@latest

# Install pnpm
npm i -g pnpm
```
