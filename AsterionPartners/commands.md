| Команда | Описание | Пример | Права |
| --- | --- | --- | --- |
| `/addpts` | Добавить партнёру очки PTS. | `/addpts partner:"SkyForge" amount:500` | AST Admin |
| `/partner_add` | Зарегистрировать партнёра и (опционально) привязать сервер. | `/partner_add name:"SkyForge" guild_id:1234567890` | AST Admin |
| `/partner_remove` | Удалить партнёра и его представителей. | `/partner_remove name:"SkyForge"` | AST Admin |
| `/setlevel` | Установить уровень партнёрства вручную. | `/setlevel partner:"SkyForge" level:2` | AST Admin |
| `/migrate` | Применить миграции базы данных ConCord. | `/migrate` | AST Admin |
| `/partner_leaderboard` | Топ партнёров по PTS. | `/partner_leaderboard` | AST Admin |
| `/partner_addrep` | Добавить представителя партнёра. | `/partner_addrep name:"SkyForge" user:@Mod` | AST Admin |
| `/partner_reps` | Список представителей выбранного партнёра. | `/partner_reps name:"SkyForge"` | ConCord (партнёрские роли) |
| `/feedback` | Отправить отзыв или репорт команде ASTERION. | `/feedback partner_name:"SkyForge" message:"Нужна поддержка"` | ConCord |
| `/partner_info` | Посмотреть уровень, PTS и привязку сервера. | `/partner_info name:"SkyForge"` | ConCord |
| `/partner_me` | Посмотреть свои данные и сервер. | `/partner_me` | ConCord |
| `/partner_help` | Справка по доступным командам. | `/partner_help` | ConCord |
| `/status` | Проверить состояние ConCord-интеграции. | `/status` | ConCord |
