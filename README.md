# webssh
## Introduction
Web based ssh container based from treehouses alpine image. About webssh more can be view [here](https://pypi.org/project/webssh/).
## Installations:
```bash
git clone https://github.com/ajanpinyo/web-ssh.git
cd webssh
docker build -t ajanpinyo/web-ssh .
```
## Usage:
- After build the docker image can run as a daemon service with default port 8022

   ``docker run --name web-ssh --restart always -p 8022:8022 -d ajanpinyo/web-ssh``
- Open a browser and navigate to the ``serverip:8022``
