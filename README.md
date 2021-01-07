# docker_img_size

Tiny utility for checking Docker image sizes. It is for those images that you've already pulled or which you've built on your system. Basically any image that is listed under ```docker images ls```.

## Installation

Run these commands as root.

```sh
curl \
    -L https://raw.githubusercontent.com/tthordarson/docker_img_size/main/docker_img_size \
    -o /usr/local/bin/docker_img_size
chmod +x /usr/local/bin/docker_img_size
```

So, for any distros that have sudo, you can do it the following way.

```sh
sudo curl \
    -L https://raw.githubusercontent.com/tthordarson/docker_img_size/main/docker_img_size \
    -o /usr/local/bin/docker_img_size
sudo chmod +x /usr/local/bin/docker_img_size
```

## Usage

```sh
docker_img_size [name ofimage]
```

### Example

```sh
docker_img_size ubuntu
```