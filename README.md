# 👋 Привет, я Данил Сейтназаров!

**Backend разработчик.** Строю надёжные микросервисы, проектирую доменные модели и люблю чисто написанный код. Основной стек — C# / .NET, активно развиваюсь в Go.

---

## 💻 Стек технологий

<div align="center">

![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET%20Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)

</div>

<div align="center">
  
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![MinIO](https://img.shields.io/badge/MinIO-C72E49?style=for-the-badge&logo=minio&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-4285F4?style=for-the-badge&logo=grpc&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![ElasticSearch](https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white)

</div>

---

## 📌 Опыт

### **Maestro** — Backend Developer *(2025 — н.в.)*

Участвую в разработке коммерческого Digital Signage продукта.

- Проектирование доменной модели по принципам DDD — агрегаты, Value Objects, бизнес-инварианты
- Разработка REST API в рамках Clean Architecture на основе контрактов с Frontend
- Настройка gRPC взаимодействия между микросервисами, разработка SharedKernel (Result Pattern, общие контракты)
- Внедрение CQRS через MediatR, покрытие бизнес-логики интеграционными тестами (Testcontainers)
- Реализация загрузки файлов в S3 через паттерн Presigned URL

---

## 🚀 Пет-проекты

### [Subscription System](https://github.com/maze37/SubscriptionSystem) `C#`

Сервис управления подписками. Полный жизненный цикл — триал, активация, смена плана, отмена.

**Стек:** .NET 10, EF Core, PostgreSQL, MediatR, FluentValidation, Docker

- Три агрегата — User, Plan, Subscription с богатой бизнес-логикой
- Бизнес-правила: триал только один раз, нельзя иметь две активные подписки

---

### [Inventory Management System](https://github.com/maze37/InventoryManagement) `C#`

Система управления складскими запасами. REST API с Clean Architecture, DDD, CQRS.

**Стек:** .NET 10, EF Core, PostgreSQL, MediatR, FluentValidation, Testcontainers, Docker

- Доменная модель с Value Objects и защитой инвариантов
- CQRS через MediatR с ValidationBehavior pipeline
- Интеграционные тесты с реальной БД через Testcontainers

---

### [Auth Service](https://github.com/maze37/auth-service) `Go`

gRPC микросервис аутентификации. Регистрация, логин, валидация JWT токенов.

**Стек:** Go, gRPC, PostgreSQL, JWT, Docker

- Чистая архитектура: domain → service → transport
- gRPC контракт с тремя методами — Register, Login, ValidateToken
- Автоматические миграции при старте через golang-migrate

---

### [URL Shortener](https://github.com/maze37/url-shortener) `Go`

HTTP-сервис сокращения ссылок с кэшированием и статистикой переходов.

**Стек:** Go, PostgreSQL, Redis, Docker

- Асинхронный счётчик кликов через горутины — редирект не блокируется
- Кэш-стратегия: Redis → PostgreSQL с graceful degradation
- Graceful shutdown — корректное завершение текущих запросов
- Swagger UI документация

---



## 📫 Контакты

<div align="center">

[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/mazefm)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/maze37)

📧 Mazeland@yandex.ru

</div>
