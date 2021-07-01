# Awesome Dockerfiles

## Requirements

- docker
- docker-compose

## How to build docker images

To build indivisual image, go to each folder 

```
cd cpp
```

then run

```
docker build -t <image_name>:<tag_number> .
```

here `<image_name>` & `<tag_number>` will be given by you.

for example if I want to build the image of cpp docker image then

```
docker build -t cpp-light:0.0.1 .
```

this will pull the necessay images and create the image for you.


* What does `--no-cache` option do in `alpine linux`?
  
  `--no-cache` option allows not to cache the index locally, which helps to keep the containers small.




