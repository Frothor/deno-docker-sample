# deno-docker-sample


### Based on:
https://medium.com/google-cloud/deno-on-cloud-run-89ae64d1664d

## Useful commands:

**1. Running locally**
```
deno run --allow-env --allow-net main.ts
```

**2. Building image**
```
docker build -t <your username>/deno-hello-world .
```

**3. Running container**
```
docker run -p 49160:8080 -d <your username>/deno-hello-world
```

**4. Viewing logs from container**
```
docker logs <container id>
```