# hm2mqtt Container

Run [hm2mqtt](https://github.com/owagner/hm2mqtt) in a Docker container.

```
docker run docker run -p 3333:3333 \
  marmelatze/hm2mqtt \
  mqtt.server=tcp://mqtt-server:1883 \
  hm.localhost=host-ip \
  hm.host=homematic-ccu2:2001
```
