## Tips

1. How to run docker image postgres
```sh
docker run -d --name local-postgres -e POSTGRES_PASSWORD=123 -e PGDATA=/var/lib/postgresql/data/pgdata -v /users/projects/data:/var/lib/postgresql/data postgres

```