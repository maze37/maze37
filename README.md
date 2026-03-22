### 👋 Привет, я Данил Сейтназаров!

**Backend C# / .NET разработчик**. Строю надежные микросервисы и люблю чисто написанный код.

Участвовал в * Кейс-чемпионате Plekhanov Case Club & АльфаБанк, Changellenge CUP IT 2026 *

---

### 💻 Мой стек технологий

![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET%20Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-4285F4?style=for-the-badge&logo=grpc&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)


*Также знаком с:* **MongoDB, ElasticSearch, MinIO, основы Frontend**

---

### 📌 Опыт

**Maestro** — Backend Developer *(2025 — н.в.)*

Участвую в разработке коммерческого Digital Signage продукта.

- Спроектировал доменную модель по принципам DDD — агрегаты, Value Objects, защита бизнес-инвариантов
- Реализовал REST API в рамках Clean Architecture — от анализа Use Cases до готовых эндпоинтов
- Настроил gRPC взаимодействие между микросервисами, разработал SharedKernel (Result Pattern, общие контракты)
- Внедрил CQRS через MediatR, покрыл код интеграционными тестами с реальной БД (Testcontainers)
- Реализовал загрузку файлов в S3 через паттерн Presigned URL

---

### 🚀 Пет-проекты

#### [Inventory Management System](https://github.com/maze37/InventoryManagement)
Система управления складскими запасами. REST API с Clean Architecture, DDD, CQRS.

**Стек:** .NET 10, EF Core, PostgreSQL, MediatR, FluentValidation, Testcontainers, Docker

- Доменная модель с Value Objects и защитой инвариантов
- CQRS через MediatR с ValidationBehavior pipeline
- Интеграционные тесты с реальной БД через Testcontainers
- IDateTimeProvider для тестируемости временной логики

---

#### [Subscription System](https://github.com/maze37/SubscriptionSystem)
Сервис управления подписками. Полный жизненный цикл — триал, активация, смена плана, отмена.

**Стек:** .NET 10, EF Core, PostgreSQL, MediatR, FluentValidation, Docker

- Три агрегата — User, Plan, Subscription с богатой бизнес-логикой
- Invoice как Entity внутри агрегата — полная история платежей
- Бизнес-правила: триал только один раз, нельзя иметь две активные подписки
- IDateTimeProvider для тестируемости временной логики

---

### 📫 Контакты
[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/mazefm)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/maze37)
📧 Mazeland@yandex.ru
