# Howto
- tested with podman-compose v1.0.6, podman 4.3.x, netavark and aardvark-dns installed
- python ~/scripts/podman-compose --in-pod in_pod up -d squid-classic-noauth squid-icap-noauth python-icap-server --no-cache # will start only icap related squid containers
