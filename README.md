# hello_docker

build: "docker build -t hello_docker ."

run: "docker run --name my_hello_container -p 80:80 hello_docker"
