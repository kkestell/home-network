# Home Network

## Router

IP Address
:   `10.0.0.1`

Hostname
:   `openwrt.local`

Admin UI
:   [http://openwrt.local](http://openwrt.local)

## Proxmox Host

Model
:    Lenovo ThinkCentre

CPU
:    Intel Core i5-4570T @ 2.9GHz

RAM
:    8GB

IP Address
:   `10.0.0.2`

Hostname
:   `pve.local`

Admin UI
:   [https://pve.local:8006](https://pve.local:8006)

## NAS

IP Address
:   `10.0.0.50`

Hostname
:   `nas.local`

System Drive
:   Samsung SSD 850 (232.9GB, /dev/sda)

Media Pool
:   ZFS pool "media" (7.25TB)

Media Disks
:   2x WD Red 4TB (WD40EFRX) - WD-WCC4E1XNRZC0, WD-WCC4E2SHPHPP

Archive Drive
:   Seagate 14TB USB (NT177CTR)

Root Mount
:   `/` on sda2 (ext4)

Archive Mount
:   `/mnt/archive` on sdd1 (ext4)

Media Mount
:   `/mnt/media` on ZFS pool

## Proxmox VMs and Containers

### Pi-hole

Type
:   LXC

IP Address
:   `10.0.0.3`

Hostname
:   `pihole.local`

Admin UI
:   [http://pihole.local/admin](http://pihole.local/admin)

## Plex

Type
:   LXC

IP Address
:   `10.0.0.4`

Hostname
:   `plex.local`

Admin UI
:   [http://plex.local:32400/web](http://plex.local:32400/web)
