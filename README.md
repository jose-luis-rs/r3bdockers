# R3BDockers for compiling R3B software [![license](https://img.shields.io/badge/License-GPLv3-blue.svg)](COPYRIGHT) 

## Discussion Forum

For the software-related user support you can post a new topic on our [forum](https://forum.gsi.de/index.php?t=index&cat=40&).

## License

R3BDockers is distributed under the terms of the GNU General Public Licence version 3 ([GPLv3](https://github.com/jose-luis-rs/r3bdockers/blob/main/LICENSE)).

## Code of Conduct

We are committed to fostering a welcoming and inclusive environment in the R3BDockers project. Please take a moment to review our [Code of Conduct](./CODE_OF_CONDUCT.md), which outlines our expectations for all contributors and community members.

## Release Information

Please visit [releases](https://github.com/jose-luis-rs/r3bdockers/releases)

## Download

~~~bash
git clone https://github.com/jose-luis-rs/r3bdockers.git
cd r3bdockers
~~~

## Few commands to run the scripts

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

