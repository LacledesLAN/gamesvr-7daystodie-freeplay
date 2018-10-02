![Laclede's LAN 7 Days to Die Freeplay Dedicated Server](https://raw.githubusercontent.com/LacledesLAN/gamesvr-7daystodie-freeplay/master/.misc/banner-7daystodie-freeplay.png "Laclede's LAN 7 Days to Die Freeplay Dedicated Server")

This repository is maintained by [Laclede's LAN](https://lacledeslan.com). Its contents are heavily tailored and tweaked for use at our charity LAN-Parties. For third-parties we recommend using this repo only as a reference example and then building your own using [gamesvr-7daystodie](https://github.com/LacledesLAN/gamesvr-7daystodie) as the base image for your customized server.

# Linux Container
[![](https://images.microbadger.com/badges/version/lacledeslan/gamesvr-7daystodie-freeplay.svg)](https://microbadger.com/images/lacledeslan/gamesvr-7daystodie-freeplay "Get your own version badge on microbadger.com")
[![](https://images.microbadger.com/badges/image/lacledeslan/gamesvr-7daystodie-freeplay.svg)](https://microbadger.com/images/lacledeslan/gamesvr-7daystodie-freeplay "Get your own image badge on microbadger.com")

## Download

```
docker pull lacledeslan/gamesvr-7daystodie-freeplay
```

## Run Interactive Server

```
docker run -it --rm --net=host lacledeslan/gamesvr-7daystodie-freeplay ./startserver.sh -configfile=serverconfig.xml
```

## Getting Started with Game Servers in Docker

[Docker](https://docs.docker.com/) is an open-source project that bundles applications into lightweight, portable, self-sufficient containers. For a crash course on running Dockerized game servers check out [Using Docker for Game Servers](https://github.com/LacledesLAN/README.1ST/blob/master/GameServers/DockerAndGameServers.md). For tips, tricks, and recommended tools for working with Laclede's LAN Dockerized game server repos see the guide for [Working with our Game Server Repos](https://github.com/LacledesLAN/README.1ST/blob/master/GameServers/WorkingWithOurRepos.md). You can also browse all of our other Dockerized game servers: [Laclede's LAN Game Servers Directory](https://github.com/LacledesLAN/README.1ST/tree/master/GameServers).
