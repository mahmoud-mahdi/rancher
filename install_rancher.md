### Install rancher with Persistant volume
docker run -d -p 80:80 -p 443:443 --name=rancher-server -v /opt/rancher:/var/lib/rancher rancher/rancher:latest
