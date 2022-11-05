# home-pie
Ansible repository for my rasberry pi server using Arch

# roles
* common: Basic arch seupt timezone, locale-gen, hostname, hosts and pacman config
* podman: Install and configure podman to run as rootless
* monitoring: Set up prometheus, node-export and grafana
* rr: Run servarr stack with rootless podman, stack includes radarr, sonarr, prowlarr, bazarr, qbittorrent and jellyfin for a full self-hosted media server
* pi-hole: Run pi-hole with rootless podman
