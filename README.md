# JWT Authentication App

Простое веб-приложение для демонстрации аутентификации с использованием JWT токенов.

## 📌 О проекте

Приложение включает:
- Бэкенд на Node.js (Express)
- Фронтенд на чистом JavaScript
- Реализацию регистрации/входа
- Защищённые маршруты с JWT
- Хранение пользователей в памяти

## 🚀 Быстрый старт

### Предварительные требования
- Node.js v14+
- npm или yarn

### Установка
1. Клонируйте репозиторий:
git clone
2. установите зависимости:
cd backend
npm install
3. создайте файл .env в папке backend
JWT_SECRET=your_strong_secret_here
4.Запуск
cd backend node server.js
2. Откройте `frontend/index.html` в браузере

## Функционал

### Бэкенд
- `POST /register` - регистрация пользователя
- `POST /login` - вход и получение JWT токена
- `GET /protected` - защищённый маршрут (требует JWT)

### Фронтенд
- Форма регистрации
- Форма входа
- Кнопка для доступа к защищённым данным
