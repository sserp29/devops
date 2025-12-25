# IronPulse — мини‑сайт тренажёрного зала (HTML/CSS) + Docker

## Что внутри
- `site/index.html` — страница
- `site/styles.css` — стили
- `site/video.mp4` — **замени на своё видео** (по умолчанию файл‑заглушка)
- `Dockerfile` + `docker-compose.yml` — запуск через nginx

## Как запустить
1) Установи Docker
2) В папке проекта выполни:

```bash
docker compose up --build
```

3) Открой в браузере:
- http://localhost:8080

## Про видео
Положи свой файл `video.mp4` в папку `site/` (рядом с `index.html`).
