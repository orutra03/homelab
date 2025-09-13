VLAN	Name	Subnet	GW	DHCP	Notes
10	mgmt	10.10.10.0/24	10.10.10.1	.100–.199	Only admin (Proxmox, switches, AP)
20	servers	10.10.20.0/24	10.10.20.1	.100–.199	AdGuard, Caddy/Portainer/Kuma/Gitea
30	lab	10.10.30.0/24	10.10.30.1	.100–.199	Testing
40	iot	10.10.40.0/24	10.10.40.1	.100–.199	TVs, printers, etc
50	guest	10.10.50.0/24	10.10.50.1	.100–.199	Internet-only
60	storage	10.10.60.0/24	10.10.60.1	—	NFS/iSCSI OnePiece↔Nasty (static ips)
70	vpn-wg	10.10.70.0/24	10.10.70.1	—	WireGuard Clients /32
