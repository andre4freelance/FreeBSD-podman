# FreeBSD-podman

Installasi podman compose
doas pkg install py311-podman-compose

Refrence: <https://freebsdfoundation.org/blog/oci-containers-on-freebsd/>
<https://docs.vultr.com/how-to-install-podman-on-freebsd-14-0>


andre@FreeBSD:~ $ ifconfig
em0: flags=1008843<UP,BROADCAST,RUNNING,SIMPLEX,MULTICAST,LOWER_UP> metric 0 mtu 1500
	options=48525bb<RXCSUM,TXCSUM,VLAN_MTU,VLAN_HWTAGGING,JUMBO_MTU,VLAN_HWCSUM,TSO4,LRO,WOL_MAGIC,VLAN_HWFILTER,VLAN_HWTSO,HWSTATS,MEXTPG>
	ether bc:24:11:a6:96:88
	inet 192.168.100.97 netmask 0xffffff00 broadcast 192.168.100.255
	media: Ethernet autoselect (1000baseT <full-duplex>)
	status: active
	nd6 options=29<PERFORMNUD,IFDISABLED,AUTO_LINKLOCAL>
lo0: flags=1008049<UP,LOOPBACK,RUNNING,MULTICAST,LOWER_UP> metric 0 mtu 16384
	options=680003<RXCSUM,TXCSUM,LINKSTATE,RXCSUM_IPV6,TXCSUM_IPV6>
	inet 127.0.0.1 netmask 0xff000000
	inet6 ::1 prefixlen 128
	inet6 fe80::1%lo0 prefixlen 64 scopeid 0x2
	groups: lo
	nd6 options=21<PERFORMNUD,AUTO_LINKLOCAL>