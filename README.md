# Notification Discord Bot

Discord bot that sends a Discord and Twitter message when there is a new lending or renting in reNFT.

![image](https://github.com/re-nft/notification-discord-bot/assets/38793207/46879a9d-8b56-4373-a88b-69d79b8c8d98)

## Install and run

```bash
poetry install
poetry run python notification_discord_bot/main.py
```

## Format

```bash
poetry run isort .
poetry run black .
```

## Lint

```bash
poetry run pylint --recursive=y
```

## Run tests

```bash
poetry run pytest
```
