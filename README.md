# Docker-Pixelmon 1.12.2-8.3.3
![ydaft](https://forthebadge.com/images/badges/you-didnt-ask-for-this.svg)
<br>
![Maintenance](https://img.shields.io/badge/Maintained%3F-no-red.svg) 
<br>

DockerFile for Pixelmon Mod
## Versions
pixelmon reforged 1.12.2-8.3.3<br/>
spongeforge 1.12.2-2838-7.3.0<br/>
forge 1.12.2-14.23.5.2854<br/>

### Build from Source
```bash
git clone https://github.com/gforke97/docker-pixelmon.git
cd docker-pixelmon
nano Dockerfile # if you want to change something
docker build . -t pixelmon
docker run -d -p 25565:25565/tcp -p 25565:25565/udp pixelmon
```
#### Enjoy
