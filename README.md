# orc

Наша работа в `doc/HLD/` — это отличный **высокий уровень концептуального дизайна** (High-Level Design Document).

### Что у нас есть (плюсы):

- ✅ **Оглавление (CONTENTS.md):** Структурированный план.
- ✅ **Исследование рынка и технологий:** Мы глубоко разобрали конкурентов, архитектуру и риски.
- ✅ **Архитектурные решения:** Restate + Windmill, Multi-Runtime, Saga Patterns.
- ✅ **Бизнес-стратегия:** SaaS + Consulting + OSS.

### Чего не хватает для полноценного PRD:

1. **Детальные функциональные требования:**

   - User Stories (например: "Как менеджер, я хочу видеть Reasoning Tree агента, чтобы понимать его логику").
   - Acceptance Criteria (что считается "готовым" для каждой фичи).

2. **Технические спецификации:**

   - API Endpoints (например, как выглядит REST API для запуска воркфлоу).
   - Схемы данных (таблицы в Postgres, форматы логов).
   - Диаграммы архитектуры (Sequence Diagrams, Component Diagrams).

3. **UX/UI требования:**

   - Wireframes или Mockups (как выглядит Flow Builder).
   - User Flows (шаг за шагом).

4. **Нефункциональные требования:**

   - Performance (SLA: 99.9% uptime, latency <100ms).
   - Security (как мы храним ключи API, compliance с GDPR/SOC2).
   - Scalability (сколько агентов может выдержать система).

5. **План реализации:**

   - Roadmap (Q1: MVP Core, Q2: UI и т.д.).
   - Risk Assessment (что если Restate будет куплен?).
   - Success Metrics (MAU, Conversion Rate).

6. **Другие разделы PRD:**
   - Stakeholders и Roles.
   - Dependencies (какие внешние сервисы нужны).
   - Testing Strategy.
