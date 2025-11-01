# ASCEND Ecosystem Documentation

## Overview
Статичный HTML сайт-документация для экосистемы ботов ASCEND, готовый к деплою на Netlify через GitHub. Содержит полную информацию о трёх Discord-ботах:
- **AsterionEvents**: Управление мероприятиями и наградами
- **AsterionMonitor**: Система уровней, XP и рангов
- **AsterionPartners**: Партнёрская программа ConCord

## Project Structure
- `index.html` - Основной статичный HTML файл со встроенными стилями и скриптами
- `attached_assets/` - Прикреплённые файлы (оригинальный дизайн)
- `README.md` - Информация о проекте

## Design
Дизайн взят из оригинального сайта AsterionPartners:
- Темная цветовая схема с cyan и violet акцентами
- Градиентный фон с радиальными эффектами
- Карточки с тенями и размытием
- Аккордеоны для организации команд
- Кнопки копирования для команд
- Адаптивный layout для мобильных устройств

## Recent Changes
- **2025-10-20**: Преобразование из MkDocs в статичный HTML
  - Удалена MkDocs конфигурация
  - Создан единый index.html с дизайном из astpartners
  - Добавлена правильная ссылка Discord: https://discord.gg/3pRjpqH454
  - Настроен простой HTTP сервер для разработки
  - Готово к деплою на Netlify

## Development
Для локальной разработки используется встроенный Python HTTP сервер:
```bash
python -m http.server 5000
```

Сервер запускается на порту 5000 и обслуживает статичный HTML файл.

## Deployment
Сайт готов к деплою на Netlify:
1. Загрузите репозиторий на GitHub
2. Подключите репозиторий к Netlify
3. Build settings:
   - Build command: (оставить пустым)
   - Publish directory: `/` (корневая директория)
4. Деплой произойдёт автоматически

Альтернативно, можно использовать Replit Deployment:
- Тип: Autoscale
- Run: `python -m http.server 5000`

## Features
- ✅ Чистый статичный HTML (без зависимостей)
- ✅ Встроенные стили (CSS in HTML)
- ✅ Встроенные скрипты (JavaScript in HTML)
- ✅ Копирование команд в буфер обмена
- ✅ Адаптивный дизайн
- ✅ SEO meta-теги
- ✅ Иконка Discord с SVG
- ✅ Готов к деплою на Netlify/Vercel/GitHub Pages

## Discord Link
Ссылка на Discord сервер: https://discord.gg/3pRjpqH454
(присутствует в навигации и в футере)

## Technologies
- HTML5
- CSS3 (встроенные стили с CSS Variables)
- Vanilla JavaScript (для функции копирования)
- Python HTTP Server (для разработки)
