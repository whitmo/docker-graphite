To run:

```
docker run -d -p 8888:8000 \
           --volumes-from carbon \
           --name graphite famly/graphite
```
