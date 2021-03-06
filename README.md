# studying-docker

Repository created to study Docker. This Docker container, when executed, generates a .txt file that says "This is my first container!".

### Running the project

It's necessary to have `Git` and `Docker` installed in your machine.  
You can download Git [here](https://git-scm.com/downloads) and Docker [here](https://www.docker.com/products/docker-desktop).
Important: you need to enable **File Sharing** in Docker for the directory of the project.

- Access the desired directory through `cmd` and clone the project  
`git clone https://github.com/lorenapnmarcon/studying-docker.git`
- Build the container with Docker Compose  
`docker-compose up -d`
- Stop the service  
`docker-compose stop`
- Check for a file named **hello_docker.txt** in your directory.

### Authors

- [**Lorena Marçon**](https://github.com/lorenapnmarcon)

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
