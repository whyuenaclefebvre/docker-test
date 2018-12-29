# Docker-Test repo

### This repo is for experimenting Docker functionalities and see files created in this repo to be directly copied to the docker container.

```bash
  docker container run -d p 8080:80 -v $(pwd):/usr/share/nginx/html --name nginx-website nginx
```

The last . indicates we want the image to be built based on our `Dockerfile`.
```bash
  docker image build -t whyuenaclefebvre/nginx-website .
```

To push the new image to Docker Hub,
```bash
  docker push whyuenaclefebvre/nginx-website
```
> `docker login` may be required 
