# HTML5CamDocker
HTML5 WebCam from a Docker Container 

##

Test it with one commnad 

```
$docker run -p 8000:8000 yassermog/html5_cam_docker --detach    
```

( http://localhost:8000 )


## Build Localy 
clone the code and change the directory to the folder 

build the image 

```
$ docker build -t testcam .
```

run the docker container 

```
$ docker run -p 8000:8000 testcam --detach
```

enjoy !

( http://localhost:8000 )
