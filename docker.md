docker exec -it d6ddccf98404 bash

docker cp wine/wine.data d6ddccf98404:/home/jovyan/wine.data

docker run -v /home/user/docker_project:/home/jovyan -p 10000:8888 quay.io/jupyter/scipy-notebook:2024-08-30

docker run -v /home/user/docker_project:/home/jovyan -p 10000:8888 .

docker build .

docker run -v /home/user/docker_project:/home/jovyan -p 10000:8888 sha256:c4f0f879eddd143b42e326304d78afd0dbff4f2f7e1fa98c74fc363e575cfd03