# HTML5CamDocker
HTML5 WebCam from a Docker Container 

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
