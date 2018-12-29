# Docker-Test repo

### This repo is for experimenting Docker functionalities and see files created in this repo to be directly copied to the docker container.

```bash
  docker container run -d p 8080:80 -v $(pwd):/usr/share/nginx/html --name nginx-website nginx
```
