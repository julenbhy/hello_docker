# hello_docker

build: "docker build -t hello_docker_image ."

run: "docker run --name hello_container -p 80:80 hello_docker_image"
