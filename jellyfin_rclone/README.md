# jellyfin_rclone

jellyfin + alist + rclone

## Installation

1. Clone the repository:
```bash
git clone https://github.com/puzzlemoondev/jellyfin_rclone.git
```

2. Install docker and docker-compose

3. Install [rclone docker volumn plugin](https://rclone.org/docker/)

4. Setup rclone config

5. Build and run the docker-compose file:
```bash
cd jellyfin_rclone
docker-compose up -d
```

## Update

```bash
cd jellyfin_rclone
docker-compose pull && docker-compose up -d --force-recreate
```
