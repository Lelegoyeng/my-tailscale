### Simple setup running on docker

``
docker run -d --rm --privileged --network host --device /dev/net/tun tailscale/tailscale tailscaled
``

### login and request exit-node
``
docker exec -it <container_id> tailscale up --advertise-exit-node --hostname NAMA_MESIN
``
