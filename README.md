# R-docker
R 3.4.4 in docker container

Docker image containing R 3.4.4

In detail, the image is set up with:
 - Ubuntu 18.04
 - R 3.4.4
   - ggplot

To run R you can do the following (this will mount the directory `/home/working` of the container to the current working directory on your local machine):
```bash
$ docker run -it --rm -v $(pwd):/home/working -w /home/working chrishah/r-docker R
```
