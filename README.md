<h1 align="center">Vladimir Pashkin</h1>

<p align="center">
  <strong>Fullstack Developer • Product Engineer • Founder of ONLAY</strong>
</p>

<p align="center">
  TypeScript • Next.js • NestJS • PostgreSQL • AI Systems
</p>

<p align="center">
  <a href="https://onlay.ru">ONLAY</a>
  ·
  <a href="https://t.me/pashkinva">Telegram</a>
  ·
  <a href="mailto:vldmrpashkin@gmail.com">Email</a>
</p>

---

## Обо мне

Я fullstack-разработчик и создатель продуктовых веб-систем.

Основное направление моей работы — проектирование и разработка прикладных SaaS-продуктов: от пользовательского интерфейса и бизнес-логики до базы данных, фоновых процессов, серверной инфраструктуры и production-деплоя.

Сейчас мой основной проект — **ONLAY**, платформа для управляемого роста B2B-продаж.

В работе уделяю особое внимание:

- архитектуре продукта и разделению ответственности между компонентами;
- типобезопасной бизнес-логике;
- надежным фоновым процессам и очередям;
- email-инфраструктуре и доставляемости;
- автоматизации разработки и эксплуатации;
- применению AI-агентов в реальных production-процессах.

---

## ONLAY

### Платформа для управляемого роста B2B-продаж

**ONLAY** — самостоятельный SaaS-продукт, объединяющий инструменты для автоматизации B2B-продаж и коммуникации с клиентами.

Это не просто сервис email-рассылок. Email-инфраструктура является одним из модулей платформы наряду с управлением кампаниями, базами контактов, аналитикой, автоматизированными действиями и другими инструментами роста продаж.

<p>
  <a href="https://onlay.ru">
    <img src="https://img.shields.io/badge/Website-onlay.ru-111827?style=for-the-badge" alt="ONLAY website">
  </a>
</p>

### Что реализовано

- управление B2B email-кампаниями;
- собственная SMTP-инфраструктура;
- очереди отправки и фоновые workers;
- управление контактами и получателями;
- базовая и глубокая проверка email-адресов;
- SPF, DKIM и DMARC-инфраструктура;
- аналитика кампаний;
- формы, лендинги и token-based действия;
- административный интерфейс;
- самостоятельный серверный API;
- production-деплой на собственный VPS;
- автоматизация миграций, сборки и обновления сервисов.

### Архитектура

```text
Next.js web application
        │
        ▼
NestJS API
        │
        ├── PostgreSQL / Prisma
        ├── Redis queues
        ├── Mail workers
        ├── SMTP infrastructure
        └── Analytics and background jobs
```

### Технологии ONLAY

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Bun](https://img.shields.io/badge/Bun-000000?style=flat-square&logo=bun&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-0F172A?style=flat-square&logo=tailwindcss&logoColor=38BDF8)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=111111)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)

---

## AI-агенты и автоматизация

Разрабатываю системы, в которых специализированные AI-агенты выполняют отдельные этапы сложных workflow:

- исследование данных;
- анализ сайтов и конкурентов;
- подготовка контентных стратегий;
- создание технических заданий;
- генерация и проверка материалов;
- маршрутизация задач между виртуальными отделами;
- автоматизированное тестирование;
- подготовка изменений к production-деплою.

Один из текущих проектов — архитектура **AI SEO Copilot**:

```text
Crawler
  → Site Analysis
  → Market Research
  → Content Plan
  → Topic Research
  → Content Brief
  → Article Draft
```

Каждый этап имеет отдельную доменную модель, детерминированную валидацию, хранение состояния и трассируемый workflow.

---

## Основной стек

### Frontend

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-111111?style=for-the-badge&logo=next.js&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-0F172A?style=for-the-badge&logo=tailwindcss&logoColor=38BDF8)

### Backend and data

![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Bun](https://img.shields.io/badge/Bun-000000?style=for-the-badge&logo=bun&logoColor=white)

### Infrastructure

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=111111)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-1F2937?style=for-the-badge&logo=git&logoColor=F05032)

---

## Featured projects

### ONLAY

SaaS-платформа для управляемого роста B2B-продаж.

Проект включает frontend-приложение, самостоятельный backend API, PostgreSQL, Redis, фоновые workers, email-инфраструктуру и собственный production-контур.

**Stack:** Next.js, React, TypeScript, NestJS, PostgreSQL, Prisma, Redis, Bun, Postfix, Nginx

**Website:** https://onlay.ru

---

### AI SEO Copilot

Многоэтапная агентная система для исследования сайтов, анализа рынка, подготовки контентной стратегии и генерации материалов.

**Stack:** TypeScript, NestJS, PostgreSQL, Prisma, Bun, LLM providers, agent workflows

---

### pokemons-fights

Интерактивная Pokémon battle arena с пошаговыми механиками, погодными эффектами и уникальными способностями персонажей.

**Stack:** Next.js 16, React, TypeScript, Tailwind CSS

**Repository:** https://github.com/vexel-prod/pokemons-fights

---

### set-engine-site

Коммерческий сайт для ООО «СЭТ».

**Stack:** Next.js, React, TypeScript

**Website:** https://set-engine.ru  
**Repository:** https://github.com/vexel-prod/set-engine-site

---

### refla-service-site

Коммерческий сайт услуг по установке зеркал на входные двери с интеграцией заявок через Telegram.

**Stack:** Next.js, React, TypeScript, Telegram API

**Website:** https://refla.ru  
**Repository:** https://github.com/vexel-prod/refla-service-site

---

## Подход к разработке

```
Product requirements
        ↓
Domain model
        ↓
Application architecture
        ↓
Typed implementation
        ↓
Automated verification
        ↓
Production deployment
        ↓
Monitoring and iteration
```

Мне интересны не отдельные страницы или изолированные компоненты, а разработка законченных продуктов, которые решают бизнес-задачи и способны стабильно работать в production.

---

## Контакты

- Telegram: https://t.me/pashkinva
- Email: vldmrpashkin@gmail.com
- ONLAY: https://onlay.ru

---

## English

Fullstack Developer, Product Engineer, and creator of **ONLAY** — a SaaS platform for managed B2B sales growth.

I design and build production-grade web products end-to-end: frontend applications, backend APIs, databases, background workers, email infrastructure, deployment pipelines, and AI-driven workflows.

**Core stack:** TypeScript, React, Next.js, NestJS, PostgreSQL, Prisma, Redis, Bun, Linux.
````
