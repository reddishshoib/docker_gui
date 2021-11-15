# docker_gui
Running gui application in docker container
Making docker image using dockerfil
   docker build -t dockerfile image_name:version .

Running Firefox directly from docker image
  sudo docker run -e DISPLAY  --net=host  image_name:version
