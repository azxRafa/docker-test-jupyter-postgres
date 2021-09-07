docker exec -it 8c8dc5d6aef1 bash

docker cp wine.data 8c8dc5d6aef1:/home/jovyan/wine.data


docker run -v /home/rafa/Desktop/docker:/home/jovyan/ -p 8888:8888 jupyter/scipy-notebook:33add21fab64

docker run -v /home/rafa/Desktop/docker:/home/jovyan/ -p 8888:8888 4cc96676d0e9



docker build -t my_notebook .


docker run -v /home/rafa/Desktop/docker:/home/jovyan/ -p 8888:8888 my_notebook
