Статус workflow: [![Main Kittygram workflow](https://github.com/Gasuaska/kittygram_final/actions/workflows/main.yml/badge.svg)](https://github.com/Gasuaska/kittygram_final/actions/workflows/main.yml)

# 🐾 Kittygram

**Kittygram** — это веб-приложение, где пользователи могут делиться фотографиями, историями и достижениями своих котиков. Проект создан для всех, кто любит кошек и хочет показать миру, какие они замечательные.

## 🚀 Возможности

- 🐱 Регистрация и авторизация пользователей
- 📸 Публикация фотографий котиков
- ✍️ Добавление достижений
- 🔎 Просмотр профилей других котиков

## 💻 Технологии

### Backend:
- Python 3.9
- Django
- Django REST Framework
- PostgreSQL
- Gunicorn

### Frontend:
- React
- JavaScript
- HTML/CSS

### DevOps:
- Docker
- Docker Compose
- Nginx
- GitHub Actions (CI/CD)
- Yandex.Cloud (или другой сервер)

## 🛠️ Установка локально

1. Клонируйте репозиторий:
git clone https://github.com/<ваш-аккаунт>/kittygram.git
cd kittygram
Создайте .env файл по примеру (пример хранится в .env.example) и укажите настройки.

2. Соберите и запустите контейнеры:

docker compose up --build
Проект будет доступен по адресу:
📍 http://localhost:9000

🌍 Демо
Проект задеплоен и доступен по адресу:
🔗 https://gasuaska-kittygram.zapto.org

📦 CI/CD
Автоматический деплой настроен через GitHub Actions:

Тесты запускаются при пуше в ветку main

Образы frontend, backend и gateway пушатся в DockerHub

После сборки проект разворачивается на сервере по SSH

👤 Автор
Проект выполнен в рамках учебной программы.
Автор: gasuaska
