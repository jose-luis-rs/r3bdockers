# R3BDockers for R3B

docker images

docker build -t ubuntu2504 -f Dockerfile_ubuntu2504 .

docker run -it ubuntu2504 /bin/bash

podman run -it --rm --entrypoint sh docker.io/r3bdockers/ubuntu2504:latest

podman run -it docker.io/r3bdockers/ubuntu2404_cpp17_jan24p5_v18.8.2

podman run -it docker.io/r3bdockers/fedora42_cpp17_jan24p5_v18.8.2 bash

docker rmi -f <id_image>

podman login docker.io

podman tag localhost/debian13_base:latest docker.io/r3bdockers/debian13_base:latest

podman push docker.io/r3bdockers/ubuntu2404_base:latest

