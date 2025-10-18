/**
 * @file: techContext.md
 * @description: Шаблон технологического контекста Desktop Organizer.
 * @dependencies: memory-bank/systemPatterns.md
 * @created: 2025-10-17
 */

# Tech Context

- **Технологический стек:** .NET 8, WPF для UI, C# для бизнес-логики, использование официального HTTP-клиента `HttpClient` для интеграции с OpenRouter.
- **Инструменты разработки:** Visual Studio 2022 / JetBrains Rider, Git, pre-commit с `dotnet format` и StyleCop Analyzer, Serilog для логирования.
- **Деплой/CI-CD:** Ручная сборка и публикация MSIX/Setup через Visual Studio, опционально GitHub Actions для автоматической сборки и прогонки тестов.
- **Качество кода:** SOLID, KISS, DRY; статический анализ StyleCop, unit-тесты xUnit для ключевой логики сортировки; обязательные code review записи в документации.
- **Дата последнего обновления:** 2025-10-17
