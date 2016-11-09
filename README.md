# ubuntu-dnsmasq

## start
docker run -d -p 8888:8888 [-e DOMAIN=domain-name] -e DISCOVERY=HOST --net=local-bridge --name dnsmasq moremagic/ubuntu-dnsmasq
