# my-docker-container
this is kali in docker with tools 

```bash
docker run -dt -p 3000:3000 -p 80:80 -p 8080:8080 -p 5001:5001 --privileged --net=host --name kali mrscratchcat/kali-tools
