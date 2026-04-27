# 👋🏻 Привет, я Сейтназаров Данил!

<div align="center">
**Backend Developer (.NET / C#).**  
Работаю в команде над backend-сервисами: быстро погружаюсь в задачи, держу фокус на результате и довожу решения до продакшена.  
Ценю понятную коммуникацию, качественный код и архитектуру, которую удобно развивать.

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

## 📌 Опыт

### Maestro (Startup) — Backend Developer (2025 — н.в.)

- Спроектировал и реализовал AdminService для управления медиаконтентом и плейлистами.
- Реализовал загрузку и обновление файлов до 1 ГБ через S3 Presigned URL (audio/video/image).
- Спроектировал доменную модель плейлистов по DDD: агрегат Playlist, Value Objects, бизнес-инварианты.
- Реализовал жизненный цикл плейлиста: draft -> published -> active.
- Настроил взаимодействие AdminService и MediaStorageService через gRPC (upload/download/delete).

---

## 🚀 Учебные проекты

### [Subscription System](https://github.com/maze37/SubscriptionSystem) `C#`

Сервис управления подписками. Полный жизненный цикл — триал, активация, смена плана, отмена.

**Стек:** .NET 10, EF Core, PostgreSQL, MediatR, FluentValidation, Docker

- Три агрегата — User, Plan, Subscription с богатой бизнес-логикой
- Бизнес-правила: триал только один раз, нельзя иметь две активные подписки

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
