# Go E-commerce

## Start Backend

```sh
make start_back
ps aux | grep gostripe_api
```

## Stop Backend

```sh
make stop_back
ps aux | grep gostripe_api
```

## Start Web

```sh
STRIPE_KEY=<stripe publishable key> STRIPE_SECRET=<stripe secret> go run ./cmd/web
```

## Run Migrations

```sh
cd migrations
soda migrate
```
