# HTML5CamDocker

HTML5 WebCam from a Docker Container 
By : Mohammed Yasser Moghrabiah <a href="https://www.facebook.com/mohammedyassermoghrabiah/">Facebook</a> <a href="https://www.linkedin.com/in/yassermog/"> linkedin</a>
source (https://github.com/yassermog/HTML5CamDocker)

## Download and Run From DockerHub:

Download and Test it with one command  

```
$ docker run -d -p 127.0.0.1:8000:8000 --name html5cam yassermog/html5_cam_docker 
```

### Test it 

( http://localhost:8000 )

### Remove it  

```
$ docker stop html5cam | docker rm html5cam
```

## (optional) Customize it and Build it Locally  : 

You can have your own version by following these steps: 

- clone the code and change the directory to the folder
- modify the index.html  

- build the image 

	```
	$ docker build -t testcam .
	```

- run the docker container 

	```
	$ docker run -p 8000:8000 testcam --detach
	```

( http://localhost:8000 )

enjoy !