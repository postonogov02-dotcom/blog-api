# Blog API

Простое REST API для блога на FastAPI.

## Features
- Создание постов
- Просмотр всех постов
- Просмотр конкретного поста
- Удаление постов
- SQLite база данных
- Docker контейнеризация

##  Links
- **API Documentation**: http://localhost:8000/docs (after running locally)
- **Author**: [Максим] - Python Backend Developer

## Quick Start

### Локальный запуск (без Docker)
```bash
pip install -r requirements.txt
uvicorn app.main:app --reload

