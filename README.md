# Telegram anonimous chat bot [![My Telegram](https://img.shields.io/badge/Telegram-Kladmen228_bot-blue)](https://t.me/kladmen228_bot)

## Requirements:

| Library          | Version  |
|------------------|----------|
| stegapy          | 0.0.1    |
| googletrans      | 4.0.0rc1 |
| pyzbar           | 0.1.8    |
| PyTelegramBotAPI | 3.7.6    |
| Pillow           | 7.1.0    |
| psycopg2-binary  | 2.8.6    |
| vk_api           | 11.7.0   |
| qrcode           | 6.1      |

## Buildpacks (heroku only)

| Buildpack | Link                                               |
|-----------|----------------------------------------------------|
| apt       | https://github.com/heroku/heroku-buildpack-apt.git |

## Aptfile (heroku only)

| Package     | Version |
|-------------|---------|
| libzbar-dev | None    |

## Procfile (heroku only)

| worker: python botinok.py |
|---------------------------|
