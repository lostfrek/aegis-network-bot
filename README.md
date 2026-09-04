# AEGIS NETWORK — Telegram-бот

Бот для продажи VPN-подписок AEGIS NETWORK. Форк [Bedolaga Bot](https://github.com/BEDOLAGA-DEV/remnawave-bedolaga-telegram-bot) с интеграцией [Remnawave](https://github.com/remnawave/backend).

## Инфраструктура

| Сервис | Адрес | Хостинг |
|---|---|---|
| Панель Remnawave | panel.nikitabronishtov.com | DigitalOcean |
| Бот (backend API) | api.nikitabronishtov.com | DigitalOcean |
| Личный кабинет | aegis.nikitabronishtov.com | DigitalOcean |

Всё развёрнуто через Docker Compose на одном дроплете (бот + Postgres + Redis + кабинет + Caddy).

## Связанные репозитории

- Личный кабинет: [lostfrek/aegis-network-cabinet](https://github.com/lostfrek/aegis-network-cabinet)
