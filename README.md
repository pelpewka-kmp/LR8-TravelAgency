# Travel Agency — Лабораторна робота №8

## Локальний запуск через Docker

З кореневого каталогу проєкту виконайте:

```bash
docker build -t travel-agency .
docker run --name travel-agency -d -p 8080:80 travel-agency
```

Відкрийте http://localhost:8080

Зупинити контейнер:
```bash
docker stop travel-agency
docker rm travel-agency
```

## Структура

- `index.html` — вебсторінка туристичної агенції.
- `Dockerfile` — інструкції для створення Docker-образу Nginx.
