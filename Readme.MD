# docker-javaws

Run web applets in Firefox and Oracle Java 8

`docker run -ti --rm -e DISPLAY=$DISPLAY -e HOSTNAME=$HOSTNAME -v /tmp/.X11-unix:/tmp/.X11-unix xnaveira/docker-javaws`

You might need to disable your X11 access control:

`xhost +`
