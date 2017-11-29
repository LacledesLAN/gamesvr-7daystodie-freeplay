# LL 7 Days to Die Freeplay Server

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
