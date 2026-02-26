# Quartz

```bash
$ docker build --tag quartz .

$ docker run --rm -it \
    -p 8082:8080 \
    -p 3002:3001 \
    -v /home/hasser/learning/brain:/usr/src/app/content \
    quartz
```
