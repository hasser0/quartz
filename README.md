# Quartz

```bash
$ docker build --tag quartz .

$ docker run --rm -it \
    -p 8081:8081 \
    -p 3001:3001 \
    -v /home/hasser/learning/computers:/usr/src/app/content \
    quartz

$ docker run --rm -it \
    -p 8082:8082 \
    -p 3002:3002 \
    -v /home/hasser/learning/math:/usr/src/app/content \
    quartz

```
