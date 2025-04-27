- **Attach a running container** 

```bash
docker exec -it <container_name> /bin/bash
```

**-i: interactive mode, -t: TTY terminal**

- **Start a new container with a shell**

```bash
docker run -it <image_name> /bin/bash
```