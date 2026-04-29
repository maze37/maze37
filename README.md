# 👋🏻 Привет, я Данил Сейтназаров !

<div>
  
## .NET-разработчик
  
Пишу backend-сервисы, которые понимают не только компилятор, но и люди после меня. Люблю чистые API, понятные границы между слоями и бизнес-логику, которую не нужно разбирать с фонариком.

Быстро влетаю в контекст, спокойно отношусь к горящим задачам и верю, что хороший код, нормальная коммуникация и немного юмора спасают спринт чаще, чем кажется.  

В команде я за здравый смысл, адекватный фидбек.

</div>

---

## 💻 Стек технологий

<div align="center">

![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=c-sharp&logoColor=white)
![.Net](https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white)
![ASP.NET](https://img.shields.io/badge/ASP.NET-%23512BD4.svg?style=for-the-badge&logo=dotnet&logoColor=white)
![Entity Framework](https://img.shields.io/badge/Entity%20Framework-%23338fcc.svg?style=for-the-badge&logo=dotnet&logoColor=white)

</div>

<div align="center">

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![MinIO](https://img.shields.io/badge/MinIO-C72E49?style=for-the-badge&logo=minio&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-%23FF6600.svg?style=for-the-badge&logo=rabbitmq&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-%23244c5a.svg?style=for-the-badge&logo=google&logoColor=white)

</div>

---
## 🚀 Проекты

### [NotificationSystem](https://github.com/maze37/NotificationSystem) `C#`

Сервис асинхронной доставки уведомлений через `email`, `push` и `webhook`-каналы.  
Решает задачу надежной обработки: постановка в очередь, обработка воркером, повторные попытки и перевод в DLQ.

**Стек:** .NET 10, ASP.NET Core, EF Core, PostgreSQL, RabbitMQ, gRPC, FluentValidation, Serilog, Seq, Docker

- Асинхронная обработка уведомлений через RabbitMQ и background worker
- Retry-механика с backoff через TTL-очереди: `10s`, `30s`, `60s`, `300s`
- Dead-letter flow при исчерпании попыток доставки
- Идемпотентность через уникальный `CorrelationId`
- Доменная модель со статусами: `Created`, `Queued`, `Processing`, `Delivered`, `Failed`, `DeadLettered`
- REST API для создания уведомлений, получения статуса и фильтрации
- gRPC-контракты для интеграции с сервисами шаблонов и доставки
- Структурированные логи через Serilog + Seq для отслеживания жизненного цикла уведомления

---

### [Subscription System](https://github.com/maze37/SubscriptionSystem) `C#`

REST API для управления пользователями, тарифными планами и подписками.  
Сервис покрывает полный жизненный цикл подписки: создание с trial-периодом или без него, смена тарифа, отмена и активация после оплаты.

**Стек:** .NET 10, ASP.NET Core, EF Core, PostgreSQL, MediatR, FluentValidation, Serilog, Seq, Docker

- Доменная модель с агрегатами `User`, `Plan`, `Subscription`
- Бизнес-правила: trial доступен только один раз, пользователь не может иметь две активные подписки
- Жизненный цикл подписки: trial, активация после оплаты, смена плана, отмена
- `Result/Error` подход для явной обработки бизнес-ошибок без бизнес-исключений
- Единый формат API-ответов: `{ result, errors, timeGenerated }`
- Централизованный маппинг ошибок в HTTP-статусы: `400`, `404`, `409`, `500`
- CQRS-style application layer: commands, queries, handlers, validators
- EF Core + PostgreSQL, repositories, Unit of Work
- Serilog + Seq для структурированных логов
- Docker Compose для локального запуска

---

### [Auth Service](https://github.com/maze37/auth-service) `Go`

gRPC микросервис аутентификации. Регистрация, логин, валидация JWT токенов.

**Стек:** Go, gRPC, PostgreSQL, JWT, Docker

- Чистая архитектура: domain → service → transport
- gRPC контракт с тремя методами — Register, Login, ValidateToken
- Автоматические миграции при старте через golang-migrate

---

### [C Labs](https://github.com/maze37/c-labs) `C`

Лабораторные работы по языку C — НИЯУ МИФИ.

- Реализация структур данных: динамические массивы, односвязные списки
- Алгоритмы сортировки: Shaker sort, Double selection sort, сравнение с qsort
- Работа с памятью: `malloc`/`realloc`/`free`, проверка утечек через Valgrind — `0 errors`
- Собственная реализация функций `string.h` (`strlen`, `strdup`, `strtok` и др.)

---

## 📫 Контакты

<div align="center">

[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/mazefm)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/maze37)

📧 Mazeland@yandex.ru

</div>
