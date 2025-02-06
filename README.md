# Home Network

## Router

<table>
<tr><td>IP Address</td><td><code>10.0.0.1</code></td></tr>
<tr><td>Hostname</td><td><code>openwrt.local</code></td></tr>
<tr><td>Admin UI</td><td><a href="http://openwrt.local">http://openwrt.local</a></td></tr>
</table>

## Google Wifi Pucks

See [OpenWrt on Google Wifi](https://github.com/kkestell/openwrt-on-google-wifi) for more information.

### Ada

<table>
<tr><td>Hostname</td><td><code>ada.local</code></td></tr>
<tr><td>IP Address</td><td><code>192.168.1.1</code></td></tr>
</table>

### Fez

<table>
<tr><td>Hostname</td><td><code>fez.local</code></td></tr>
<tr><td>IP Address</td><td><code>192.168.1.2</code></td></tr>
</table>

### Rio

<table>
<tr><td>Hostname</td><td><code>rio.local</code></td></tr>
<tr><td>IP Address</td><td><code>192.168.1.3</code></td></tr>
</table>

## Proxmox Host

<table>
<tr><td>Model</td><td>Lenovo ThinkCentre</td></tr>
<tr><td>CPU</td><td>Intel Core i5-4570T @ 2.9GHz</td></tr>
<tr><td>RAM</td><td>8GB</td></tr>
<tr><td>IP Address</td><td><code>10.0.0.2</code></td></tr>
<tr><td>Hostname</td><td><code>pve.local</code></td></tr>
<tr><td>Admin UI</td><td><a href="https://pve.local:8006">https://pve.local:8006</a></td></tr>
</table>

## NAS

<table>
<tr><td>IP Address</td><td><code>10.0.0.50</code></td></tr>
<tr><td>Hostname</td><td><code>nas.local</code></td></tr>
<tr><td>System Drive</td><td>Samsung SSD 850 (232.9GB, /dev/sda)</td></tr>
<tr><td>Media Pool</td><td>ZFS pool "media" (7.25TB)</td></tr>
<tr><td>Media Disks</td><td>2x WD Red 4TB (WD40EFRX) - WD-WCC4E1XNRZC0, WD-WCC4E2SHPHPP</td></tr>
<tr><td>Archive Drive</td><td>Seagate 14TB USB (NT177CTR)</td></tr>
<tr><td>Root Mount</td><td><code>/</code> on sda2 (ext4)</td></tr>
<tr><td>Archive Mount</td><td><code>/mnt/archive</code> on sdd1 (ext4)</td></tr>
<tr><td>Media Mount</td><td><code>/mnt/media</code> on ZFS pool</td></tr>
</table>

## Proxmox VMs and Containers 

### Pi-hole

<table>
<tr><td>Type</td><td>LXC</td></tr>
<tr><td>IP Address</td><td><code>10.0.0.3</code></td></tr>
<tr><td>Hostname</td><td><code>pihole.local</code></td></tr>
<tr><td>Admin UI</td><td><a href="http://pihole.local/admin">http://pihole.local/admin</a></td></tr>
</table>

### Plex

<table>
<tr><td>Type</td><td>LXC</td></tr>
<tr><td>IP Address</td><td><code>10.0.0.4</code></td></tr>
<tr><td>Hostname</td><td><code>plex.local</code></td></tr>
<tr><td>Admin UI</td><td><a href="http://plex.local:32400/web">http://plex.local:32400/web</a></td></tr>
</table>