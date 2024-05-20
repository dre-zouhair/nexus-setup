# NEXUS SETUP

## With Docker

MUST DO :
- change the volume path
- Update exported ports to match your repositories
- Change the admin password 


```bahs
 docker-compose up -d --build
```

Then to get the admin password :

```bash
docker exec -it [container-name]  cat /nexus-data/admin.password
```

[//]: # (8a3c97eb-5d3b-4616-bf28-e52de223d99d)

