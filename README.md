# XCA с поддержкой GOST
пример запуска
```sh
xhost +local:
docker run --rm -d -v /home/local/xca:/xca -v /tmp/.X11-unix:/tmp/.X11-unix --ipc=host albus/xca
```
