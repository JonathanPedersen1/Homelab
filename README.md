# Welcome to my homelab!
This is where i document progress regarding my homelab.

# Hardware
**Masternode:**
- RPi5 8GB
- 52pi PoE+ ssd hat
- SSD tba

**Workernode:**
- Core ultra 5 225h *(Asus NUC 15 pro)*
- 2x Crucial 24GB DDR5 5600MHz (48GB)
- 4TB Kingston KC3000 NVME SSD
- Akasa maxwell RC pro - fanless case designed for TDP of 40W, while cpu actually is 28W, leaving also headroom.

**Router**
- ASUS BE3600

**Switch**
- Netgear GS305EP, 4 ports PoE+ (30W per port) - as a cluster for learning, i can manage with 4 ports, having 2 leftover.

# OS and other
- My cluster is running k3s, with k9s as a management tool.
- Both of my nodes are running Ubuntu Server.

**Services**
- Grafana with Prometheus
- Valheim
And more to come...

# Thoughts
Id like to run pi-hole too, but havent yet because doing "surgery" on the worker (where it would reside), or doing reboots, will also make my network DNS-less which isnt viable. This project is for another node in the future.
