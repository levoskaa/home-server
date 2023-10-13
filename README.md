# My home server
### Current setup and ideas

Service | Description | Status
--- | --- | :---:
[Dynu](https://www.dynu.com) | Dynamic DNS service provider | :heavy_check_mark:
[~DDclient~](https://github.com/ddclient/ddclient) | ~Perl client used to update dynamic DNS entries~ replaced with cURL + crontab | :heavy_check_mark:
[Portainer](https://www.portainer.io) | Container management tool | :heavy_check_mark:
[Watchtower](https://containrrr.dev/watchtower/) | Solution for automating Docker container base image updates | :heavy_check_mark:
[Diun](https://crazymax.dev/diun/) | Send notifications when a Docker image is updated on a Docker registry (should be preferred over Watchtower) | :memo:
[Heimdall](https://heimdall.site) | Application dashboard and launcher | :heavy_check_mark:
[dhcp-helper](http://manpages.ubuntu.com/manpages/xenial/man8/dhcp-helper.8.html) | DHCP/BOOTP relay agent | :heavy_check_mark:
[RPi-Monitor](https://github.com/XavierBerger/RPi-Monitor) | Real time monitoring tool for embedded devices | :memo:
[Netdata](https://www.netdata.cloud) | Infrastructure monitoring and troubleshooting tool | :heavy_check_mark:
[Pi-hole](https://pi-hole.net) | DNS sinkhole | :heavy_check_mark:
[pihole-updatelists](https://github.com/jacklul/pihole-updatelists) | Automatic update tool for remote lists for Pi-hole | :heavy_check_mark:
[Commonly whitelisted domains #1](https://discourse.pi-hole.net/t/commonly-whitelisted-domains/212) | Whitelisting tips for Pi-hole | :heavy_check_mark:
[Commonly whitelisted domains #2](https://github.com/anudeepND/whitelist) | Collection of commonly whitelisted domains for Pi-Hole | :heavy_check_mark:
[The Firebog](https://firebog.net) | Adlists for Pi-hole | :heavy_check_mark:
[pihole-regex](https://github.com/mmotti/pihole-regex) | Regex filters for Pi-hole | :heavy_check_mark:
[ufw-docker](https://github.com/chaifeng/ufw-docker) | Fix for the Docker and UFW security flaw | :heavy_check_mark:
[firewalld](https://firewalld.org) | Dynamically managed firewall | :memo:
[WireGuard](https://www.wireguard.com) | VPN solution | :heavy_check_mark:
[OpenVPN](https://openvpn.net) | VPN solution | :memo:
[Jellyfin](https://jellyfin.org) | The Free Software Media System | :heavy_minus_sign:
[Samba](https://www.samba.org) | Standard Windows interoperability suite of programs for Linux | :heavy_minus_sign:
[HandBrake](https://handbrake.fr) | Open source video transcoder | :heavy_minus_sign:
[Nginx Proxy Manager](https://nginxproxymanager.com) | Reverse Proxy solution | :heavy_check_mark:
[Calibre OPDS](https://blog.slucas.fr/projects/calibre-opds-php-server/) | Web-based light alternative to Calibre content server | 📝
[Calibre-Web](https://github.com/janeczku/calibre-web) | A web app that offers a clean and intuitive interface for browsing, reading, and downloading eBooks using a valid Calibre database. | ✔️
[Nextcloud](https://nextcloud.com) | Self-hosted productivity platform | :heavy_minus_sign:
[Vaultwarden](https://github.com/dani-garcia/vaultwarden) | Unofficial Bitwarden server implementation | :heavy_check_mark:
[nCore login](https://github.com/levoskaa/ncore-login) | Scheduled login script for nCore to prevent account lock | :heavy_check_mark:
