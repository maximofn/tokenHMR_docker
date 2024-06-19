# TokenHMR docker

Dockerization of the [TokenHMR repository](https://github.com/saidwivedi/TokenHMR)

 * Repository: [https://github.com/saidwivedi/TokenHMR](https://github.com/saidwivedi/TokenHMR)

With this docker you can do this video

<p align="center">
  <img src="https://github.com/saidwivedi/TokenHMR/raw/main/assets/gymnasts_results.gif" alt="Demo GIF">
</p>

## Requisites

[Docker](https://docs.docker.com/desktop/) and [nvidia container toolkit](https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/latest/install-guide.html) must be installed.

## Usage

### Download weights

Download `data.zip` from [tokenhmr site](https://tokenhmr.is.tue.mpg.de/download.php)

### Download the image from the Docker Hub

You can download the image and run it

```bash
docker pull maximofn/token_hmr:latest
./run_app.sh
```

### Build the image

Or you can build the image and run it

```bash
./build_docker_image.sh
./run_app.sh
```
