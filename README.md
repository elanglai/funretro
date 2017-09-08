# funretro

container to run a retro board. When a build takes place it grabs the latest from https://github.com/funretro/distributed

# docker hub location

https://hub.docker.com/r/elanglai/retro/

```
$ docker build -t retro .
$ docker run -p 8080:4000 retro
```

# image only

`$ docker run -p 8080:4000 elanglai/funretro`
