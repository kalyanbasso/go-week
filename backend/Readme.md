## Backend

### Migration (Tern)

To run the migration, you need to have the `tern` binary installed. You can install it by running the following command:

```bash
tern migrate --migrations ./internal/store/pgstore/migrations/ --config ./internal/store/pgstore/migrations/tern.conf
```

or

```bash
go run cmd/tools/terndotenv/main.go
```

### Running the server

To run the server, you need to have the `tern` binary installed. You can install it by running the following command:

```bash
docker-compose up
```

### PGAdmin

Access the pgAdmin interface by visiting `http://localhost:8081` in your browser. The default username is `admin` and the default password is `admin`.
