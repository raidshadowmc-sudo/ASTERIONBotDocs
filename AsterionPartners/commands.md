| Команда | Описание | Пример | Права |
| --- | --- | --- | --- |
| `/addpts` | Добавить партнёру очки PTS. | `/addpts partner:"SkyForge" amount:500` | AST Admin |
| `/partner_add` | Зарегистрировать партнёра и (опционально) привязать сервер. | `/partner_add name:"SkyForge" guild_id:1234567890` | AST Admin |
| `/partner_remove` | Удалить партнёра и его представителей. | `/partner_remove name:"SkyForge"` | AST Admin |
| `/setlevel` | Установить уровень партнёрства вручную. | `/setlevel partner:"SkyForge" level:2` | AST Admin |
| `/migrate` | Применить миграции базы данных ConCord. | `/migrate` | AST Admin |
| `/partner_leaderboard` | Топ партнёров по PTS. | `/partner_leaderboard` | AST Admin |
| `/partner_reward` | Выдать бонус PTS/FuRY партнёру _(Добавлено в патче Concord α Patch 0.0.5a)_ | `/partner_reward name:"SkyForge" pts:250 fury:500 reason:"Сезонный бонус"` | AST Admin |
| `/partner_announcements` | Отправить объявление в канал партнёра _(Добавлено в патче Concord α Patch 0.0.5a)_ | `/partner_announcements name:"SkyForge" message:"Созвон завтра" channel_name:"announcements"` | AST Admin |
| `/partner_sync` | Форс-синхронизация слэш-команд во всех гильдиях _(Добавлено в патче Concord α Patch 0.0.5a)_ | `/partner_sync` | AST Admin |
| `/partner_audit` | Быстрая проверка настроек и активности партнёра _(Добавлено в патче Concord α Patch 0.0.5a)_ | `/partner_audit name:"SkyForge"` | AST Admin |
| `/partner_addrep` | Добавить представителя партнёра. | `/partner_addrep name:"SkyForge" user:@Mod` | AST Admin |
| `/partner_reps` | Список представителей выбранного партнёра. | `/partner_reps name:"SkyForge"` | ConCord (партнёрские роли) |
| `/partner_stats` | Расширенная статистика партнёра _(Добавлено в патче Concord α Patch 0.0.5a)_ | `/partner_stats name:"SkyForge"` | ConCord |
| `/partner_activity` | Активность партнёра по дням _(Добавлено в патче Concord α Patch 0.0.5a)_ | `/partner_activity name:"SkyForge" days:7` | ConCord |
| `/partner_daily` | Забрать ежедневный бонус PTS/FuRY _(Добавлено в патче Concord α Patch 0.0.5a)_ | `/partner_daily name:"SkyForge"` | ConCord (репы/AST) |
| `/partner_weekly` | Еженедельный бонус PTS/FuRY _(Добавлено в патче Concord α Patch 0.0.5a)_ | `/partner_weekly name:"SkyForge"` | ConCord (репы/AST) |
| `/partner_monthly` | Ежемесячный бонус PTS/FuRY _(Добавлено в патче Concord α Patch 0.0.5a)_ | `/partner_monthly name:"SkyForge"` | ConCord (репы/AST) |
| `/feedback` | Отправить отзыв или репорт команде ASTERION. | `/feedback partner_name:"SkyForge" message:"Нужна поддержка"` | ConCord |
| `/partner_info` | Посмотреть уровень, PTS и привязку сервера. | `/partner_info name:"SkyForge"` | ConCord |
| `/partner_me` | Посмотреть свои данные и сервер. | `/partner_me` | ConCord |
| `/partner_help` | Справка по доступным командам. | `/partner_help` | ConCord |
| `/status` | Проверить состояние ConCord-интеграции. | `/status` | ConCord |
