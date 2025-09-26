# Blog API

Простое REST API для блога на FastAPI.

## Features
- Создание постов
- Просмотр всех постов
- Просмотр конкретного поста
- Удаление постов
- SQLite база данных
- Docker контейнеризация

## Quick Start

### Локальный запуск (без Docker)
```bash
pip install -r requirements.txt
uvicorn app.main:app --reload
