# cheat sheet
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
## Categories
- [Docker](#docker)
- [Netcat](#netcat)
- [Wordcount](#wordcount)


## Docker
Build docker image
```sh
docker build -t imagename:tag .
```
Spin up a container. Map host port 8080 to port 80 in the container
```sh
docker run -p 8080:80 --name containername imagename:tag
```

## Netcat
Listen on port 8080 (verbose)
```sh
nc -lv 8080
```
Connect to port 8080 on localhost
```sh
nc localhost 8080
```

## Wordcount
Count number of lines
```sh
wc -l filename.txt
```
Count number of words
```sh
wc -w filename.txt
```
Count number of characters
```sh
wc -c filename.txt
```


License
----
Apache 2.0 License
