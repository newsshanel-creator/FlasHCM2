# FlasH — CM Client Mobile Competitive Platform

Многостраничный интерактивный frontend-прототип платформы FlasH по приложенному референсу и техническому заданию.

## Запуск

1. Распакуйте архив.
2. Откройте `index.html` в современном браузере. Для корректной работы некоторых функций (например, скачивания CSV) можно запустить локальный сервер:
   - Python: `python -m http.server 8000`
   - затем открыть `http://localhost:8000`

## Страницы

- Home dashboard
- Play / Matchmaking (режимы, регион, выбор карт, очередь и демо Match Found)
- Match history (фильтры, CSV export)
- Tournaments (категории и карточки событий)
- Teams & Clans (поиск, фильтры, создание демо-команды)
- Leaderboard (поиск игроков)
- Statistics (ELO chart, K/D, favorite maps)
- Friends (поиск, статусы, приглашения)
- News
- Events & Missions
- Shop
- Player Profile
- Settings
- Support
- Match Room

## Важно

Это самостоятельный frontend demo с вымышленными данными. Реальная авторизация, серверный matchmaking, live-данные, платежи, игровые серверы и постоянное сохранение требуют backend/API и не реализуются одной статической сборкой. Большинство кнопок демонстрируют интерактивные состояния в браузере.
