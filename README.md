# ZypeGitBot

> A GitHub App built with [Probot](https://github.com/probot/probot) that The Official GitHub Bot by Zype for Pull Request and Issues watch-up.

## Setup

```sh
# Install dependencies
npm install

# Run the bot
npm start
```

## Docker

```sh
# 1. Build container
docker build -t ZypeBot .

# 2. Start container
docker run -e APP_ID=<app-id> -e PRIVATE_KEY=<pem-value> ZypeBot
```

## Contributing

If you have suggestions for how ZypeBot could be improved, or want to report a bug, open an issue! We'd love all and any contributions.

For more, check out the [Contributing Guide](CONTRIBUTING.md).

## License

[ISC](LICENSE) © 2021 - 2022 Rajdeep Malakar <Rajdeep@tgeeks.cf>
