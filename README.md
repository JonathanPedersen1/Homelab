# Welcome to my homelab!
This is where i document progress regarding my homelab.

# Hardware
**Masternode:**
- RPi5 8GB
- 52pi PoE+ ssd hat
- SSD tba

**Workernode:**
- Core ultra 5 225h *(Asus NUC 15 pro)*
- Crucial 24GB DDR5 5600MHz
- WD Black 850X 1TB

**Router**
- ASUS BE3600 - *i just needed a router that didnt look like flying saucer*


**Switch**
- Netgear GS305EP, 4 ports PoE+ (30W per port) - as a cluster for learning, i can manage with 4 ports, having 2 leftover.


# Software, OS, and more
Ive chosen K3S as my kubernetes distribution, as i per now only intend to learn things like orchestration, linux, networking etc. I might check out k8s later if i ever see the need.
Both of my machines are running Ubuntu Server LTS 24.04.3. I spesifically wanted to avoid desktop environments, because it would superfluous for serveruse, and much so for a kubernetes cluster.
Regarding management, ive chosen Rancher, as it felt natural hence K3S *being* Rancher. Ive looked a tiny bit on Lens, but for now ill stick with Rancher.

# Thoughts
Ideally, id like to add another node for things like Pi-hole and mediastuff, but thats for another day. I could likely run this on the worker i already have, but that wouldnt be very redundant.
