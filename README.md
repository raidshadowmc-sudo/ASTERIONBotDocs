# ASCEND Ecosystem — Документация

Статичный HTML сайт-документация для экосистемы Discord ботов ASCEND.

## 🤖 Боты

- **AsterionEvents** — Управление мероприятиями и наградами
- **AsterionMonitor** — Система уровней, XP и рангов  
- **AsterionPartners** — Партнёрская программа ConCord

## 🚀 Деплой на Netlify

### Через GitHub (рекомендуется)

1. **Загрузите код на GitHub:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/ваш-username/ваш-repo.git
   git push -u origin main
   ```

2. **Подключите к Netlify:**
   - Зайдите на [netlify.com](https://netlify.com)
   - Нажмите "Add new site" → "Import an existing project"
   - Выберите ваш GitHub репозиторий
   - Build settings:
     - Build command: *(оставить пустым)*
     - Publish directory: `/` *(корневая директория)*
   - Нажмите "Deploy site"

3. **Готово!** Ваш сайт будет доступен по адресу `название-сайта.netlify.app`

### Через Drag & Drop

1. Зайдите на [netlify.com](https://netlify.com)
2. Перетащите всю папку проекта в область "Deploy manually"
3. Готово!

## 📁 Структура проекта

```
.
├── index.html          # Главный HTML файл (всё в одном)
├── README.md           # Этот файл
├── replit.md           # Документация для Replit
└── attached_assets/    # Оригинальные файлы дизайна
```

## 🎨 Дизайн

- Темная цветовая схема (cyan + violet акценты)
- Градиентный фон с радиальными эффектами
- Карточки с тенями и blur эффектами
- Аккордеоны для организации команд
- Кнопки копирования для команд
- Полностью адаптивный дизайн

## 🔗 Discord

Ссылка на сервер: [https://discord.gg/3pRjpqH454](https://discord.gg/3pRjpqH454)

## 💻 Локальная разработка

```bash
# Запустить локальный сервер
python -m http.server 5000

# Или с помощью Node.js
npx serve
```

Откройте [http://localhost:5000](http://localhost:5000) в браузере.

## ✨ Особенности

- ✅ Один HTML файл (без зависимостей)
- ✅ Встроенные стили и скрипты
- ✅ Работает копирование команд
- ✅ SEO оптимизация
- ✅ Готов к деплою на любой статичный хостинг
- ✅ Адаптивный дизайн для мобильных устройств

## 📝 Лицензия

> ⚠️ Licensed under the ASCEND Proprietary License v1.0  
> All Rights Reserved © 2025 ASCEND / ASTERION Team
