# immich_nfs_problem

```bash
mkdir -p /mnt/nfs_share/Homelab/immich_portainer/Immich/upload/.immich
mkdir -p /mnt/nfs_share/Homelab/immich_portainer/Immich/encoded-video/.immich
mkdir -p /mnt/nfs_share/Homelab/immich_portainer/Immich/thumbs/.immich
chown -R 1000:1000 /mnt/nfs_share/Homelab/immich_portainer/Immich
chmod -R 775 /mnt/nfs_share/Homelab/immich_portainer/Immich
rm -rf /mnt/nfs_share/Homelab/immich_portainer/Immich/upload/.immich
rm -rf /mnt/nfs_share/Homelab/immich_portainer/Immich/encoded-video/.immich
rm -rf /mnt/nfs_share/Homelab/immich_portainer/Immich/thumbs/.immich
touch /mnt/nfs_share/Homelab/immich_portainer/Immich/upload/.immich
touch /mnt/nfs_share/Homelab/immich_portainer/Immich/encoded-video/.immich
touch /mnt/nfs_share/Homelab/immich_portainer/Immich/thumbs/.immich
chown -R 1000:1000 /mnt/nfs_share/Homelab/immich_portainer/Immich
chmod -R 775 /mnt/nfs_share/Homelab/immich_portainer/Immich
mkdir -p /mnt/nfs_share/Homelab/immich_portainer/Immich/library
touch /mnt/nfs_share/Homelab/immich_portainer/Immich/library/.immich
chown -R 1000:1000 /mnt/nfs_share/Homelab/immich_portainer/Immich/library
chmod -R 775 /mnt/nfs_share/Homelab/immich_portainer/Immich/library
mkdir -p /mnt/nfs_share/Homelab/immich_portainer/Immich/profile
touch /mnt/nfs_share/Homelab/immich_portainer/Immich/profile/.immich
chown -R 1000:1000 /mnt/nfs_share/Homelab/immich_portainer/Immich/profile
chmod -R 775 /mnt/nfs_share/Homelab/immich_portainer/Immich/profile
mkdir -p /mnt/nfs_share/Homelab/immich_portainer/Immich/backups
touch /mnt/nfs_share/Homelab/immich_portainer/Immich/backups/.immich
chown -R 1000:1000 /mnt/nfs_share/Homelab/immich_portainer/Immich/backups
chmod -R 775 /mnt/nfs_share/Homelab/immich_portainer/Immich/backups

```
