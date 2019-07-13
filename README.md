# Docker Crond

### Tags
- twoboxen/docker-crond:**latest**

### Ports

### Volumes
- **/etc/crontabs/root** - the crond file used

## Running

The quickest way to get it running without integrating with a download client or media server (plex)
```
sudo docker run -v /path/to/your/crondfile:/etc/crontabs/root twoboxen/docker-crond
```
