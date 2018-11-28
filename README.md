# pING command dockerized #
This is a docker build with the linux ping command. The image is based on the Alpine Linux image.

## Build
```
$ docker build -t freelyit/ping .
```

## Run
```
$ docker run --rm freelyit/ping <ip address>
```