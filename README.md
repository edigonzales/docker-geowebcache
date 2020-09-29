# docker-geowebcache

```
docker build -t sogis/geowebcache .
```

```
docker run -p 8080:8080 sogis/geowebcache

docker run -p 8080:8080 -v ~/gwc-config:/config sogis/geowebcache
```