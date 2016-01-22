Docker example
====
This is simple image which hosted html files in `site` using nginx.

Start a container
----

```
./start
```

Stop a container
----

```
docker stop mysite
```

Remove a container
----

```
docker rm mysite
```

SSH to a container
----

You can ssh to the container and see that html files in `site` folder
are mounted to `/usr/share/nginx/html` in the container.

```
docker exec -it mysite bash
```

Container IP
----

```
docker-machine ip default
```

Container port
----

```
docker ps
```
