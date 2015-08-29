# CoreOS Services

Example docker service files for systemd (unclustered CoreOS)

#### Quick Start

On the host:

```bash
git clone https://github.com/tribou/coreos-services.git
cd coreos-services/unclustered
sudo systemctl enable `pwd`/bind.service
sudo systemctl start bind.service
```

