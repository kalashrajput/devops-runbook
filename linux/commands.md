# Linux & Docker Commands Reference

## File Operations
- `ls -la` — list all files with permissions
- `cp -r src dst` — recursive copy
- `rm -rf dir` — force delete directory

## Process Management
- `ps aux` — list all processes
- `kill -9 PID` — force kill process
- `top` — live process monitor

## Networking
- `ping host` — test connectivity
- `curl -I url` — fetch headers only
- `ss -tulnp` — show open ports

## Disk Management
- `df -h` — disk usage human readable
- `du -sh dir` — folder size

## Docker Basics
- `docker ps` — list running containers
- `docker images` — list images
- `docker run -d image` — run container detached
- `docker logs container` — view logs
- `docker exec -it container bash` — enter container
