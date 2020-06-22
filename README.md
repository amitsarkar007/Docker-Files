# Docker-Files
Using **[Docker](https://www.docker.com/)** to run **[Taiko](https://github.com/getgauge/taiko)** test scripts in a container 

## Install Docker

### Windows
* Download **[Docker Desktop for Windows](https://hub.docker.com/editions/community/docker-ce-desktop-windows/)**

### Linux
* Install Docker Engine on **[Arch](https://wiki.archlinux.org/index.php/docker#Installation)**
* Install Docker Engine on **[CentOS](https://docs.docker.com/engine/install/centos/)**
* Install Docker Engine on **[Debian](https://docs.docker.com/engine/install/debian/)**
* Install Docker Engine on **[Fedora](https://docs.docker.com/engine/install/fedora/)**
* Install Docker Engine on **[Ubuntu](https://docs.docker.com/engine/install/ubuntu/)**

### macOS
* Download **[Docker Desktop for macOS](https://hub.docker.com/editions/community/docker-ce-desktop-mac/)**

## Docker Hub
* Signup at **[Docker Hub](https://hub.docker.com/signup/)**
* Login using 
    ```
    sudo docker login --username=yourhubusername --email=youremail@company.com
    ```

## Build Docker image without previous cache
```
sudo docker build -t <name of image> -f <name of Dockerfile> . --no-cache
```

## Check Docker images
```
sudo docker images
```

## Run Docker image
```
sudo docker run <name of image>
```

## Check Docker containers
```
sudo docker container ls -a
```