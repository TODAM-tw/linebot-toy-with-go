# Line Bot Toy with GO and ngrok

## Developing Requirements

Go version `1.21` or supported by [`line-bot-sdk-go`](https://github.com/line/line-bot-sdk-go).

## Run web app

Edit the `.env` file with your `YOUR_CHANNEL_ACCESS_TOKEN` and `YOUR_CHANNEL_SECRET`

```bash
$ cp .env.example .env
$ go mod tidy
$ go run server.go
```

```bash
$ brew install ngrok

$ ngrok http 8080
```