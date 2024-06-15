# Debian 11 Ansible Test Image

[![github actions workflow status](https://img.shields.io/github/actions/workflow/status/fernandobohrer/docker-ansible-debian-11/build-test-and-push-docker-image.yml?branch=main&event=push&style=flat-square&logo=github&logoColor=white&label=Build%2C%20test%20and%20push%20docker%20image&cacheSeconds=300)](https://github.com/fernandobohrer/docker-ansible-debian-11/actions/workflows/build-test-and-push-docker-image.yml)
[![docker pulls](https://img.shields.io/docker/pulls/fernandobohrer/docker-ansible-debian-11?style=flat-square&logo=docker&logoColor=white&label=pulls&cacheSeconds=300)](https://hub.docker.com/r/fernandobohrer/docker-ansible-debian-11/)
[![amd64 docker image size](https://img.shields.io/docker/image-size/fernandobohrer/docker-ansible-debian-11?arch=amd64&style=flat-square&logo=docker&logoColor=white&label=amd64%20image%20size&cacheSeconds=300)](https://hub.docker.com/r/fernandobohrer/docker-ansible-debian-11/tags/)
[![arm64 docker image size](https://img.shields.io/docker/image-size/fernandobohrer/docker-ansible-debian-11?arch=arm64&style=flat-square&logo=docker&logoColor=white&label=arm64%20image%20size&cacheSeconds=300)](https://hub.docker.com/r/fernandobohrer/docker-ansible-debian-11/tags/)

This repository contains a `Dockerfile` that is used to create a **Debian 11** based docker container image with `ansible` and `systemd` preinstalled.

## 🚀 Motivation

The container image that is created from this repository can be used for Ansible role testing.

The `systemd` package is installed so that this container image can be used to test Ansible roles that deploy services.

## 📦 Build process

This container image is built and uploaded automatically to Docker Hub once a week and any time a commit is made or merged to the `main` branch.

## 🏷️ Tags

- `latest`: Latest stable version of `ansible`.

## ⚠️ Warning

Use this repository and the docker image that it creates at your own risk!
