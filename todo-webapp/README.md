# todo
## How to

```
# prepare
docker-compose -f docker-compose.yml up -d
docker-compose -f docker-compose.yml down
# run
DATABASE_URL='postgres://localhost:5432/todo?user=postgres&password=postgres&sslmode=disable' go run ./main.go
```

