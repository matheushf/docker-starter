# docker-starter
Getting started repository to docker

- Run with interaction
`docker run -it image_name [comand]`

- Install packages 
- Commit
`docker commit [container_id] image_name`

- Run in background
`docker run -d image_name`

- Bring runing Docker container to bash
`docker exec -it [id or name] bash`

- Build Dockerfile
`docker build -t image_name [path_dockerfile]`

- Delete after use
`docker run --rm -it image_name [command]`

..add some more later