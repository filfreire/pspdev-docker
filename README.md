# pspdev-docker

[![Publish Docker image](https://github.com/filfreire/pspdev-docker/actions/workflows/main.yml/badge.svg)](https://github.com/filfreire/pspdev-docker/actions/workflows/main.yml)


> ⚠️ Disclaimer: This fork from [pspdev-docker](https://github.com/pspdev/pspdev-docker) project might be unstable, and is edited for personal use.
> ⚠️ Please refer to official [pspdev](https://github.com/pspdev/pspdev) project for the most up-to-date approach for using `pspdev` + Docker.

## How to build

Build the image:
```shell
sudo docker build -t pspdev-docker .
```


Copy the helper script to run from local build image:
```shell
sudo cp pspdev-docker-local /usr/local/bin`
```

Or use image from docker registry:
```shell
sudo cp pspdev-docker /usr/local/bin`
```

## How to run

Use the helper script to run commands in the current directory: `pspdev-docker make`
