VLAN	Nombre	Subred	GW (pfSense)	DHCP	Rango DHCP	Notas
10	mgmt	10.10.10.0/24	10.10.10.1	Sí	.100–.199	Solo admin (Proxmox, switches, AP, tú)
20	servers	10.10.20.0/24	10.10.20.1	Sí	.100–.199	AdGuard 10.10.20.5, Caddy/Portainer/Kuma/Gitea
30	lab	10.10.30.0/24	10.10.30.1	Sí	.100–.199	VMs de pruebas/romper
40	iot	10.10.40.0/24	10.10.40.1	Sí	.100–.199	TVs, impresoras, etc.
50	guest	10.10.50.0/24	10.10.50.1	Sí	.100–.199	Internet-only
60	storage	10.10.60.0/24	10.10.60.1	No	—	NFS/iSCSI OnePiece↔Nasty (IPs fijas)
70	vpn-wg	10.10.70.0/24	10.10.70.1	No	—	Clientes WireGuard /32
