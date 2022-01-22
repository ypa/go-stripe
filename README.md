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
STRIPE_KEY=<stripe publishable key> go run ./cmd/web
```
