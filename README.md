<div align="center">

<h1>Привет, я LINESKL 👋</h1>

<h3>Full-Stack / DevOps Developer · Enterprise ERP & CRM · Clean Architecture</h3>

<p>
  <a href="https://t.me/lineskl"><img src="https://img.shields.io/badge/Telegram-@lineskl-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" /></a>
  <a href="mailto:lineskl.aliar@gmail.com"><img src="https://img.shields.io/badge/Gmail-lineskl.aliar-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" /></a>
  <a href="https://github.com/LINESKL"><img src="https://img.shields.io/badge/GitHub-LINESKL-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
</p>

<p>
  <img src="https://komarev.com/ghpvc/?username=LINESKL&label=Profile%20views&color=555555&style=for-the-badge" alt="Profile views" />
  <img src="https://img.shields.io/badge/Focus-Full--Stack%20%2B%20DevOps-0D1117?style=for-the-badge&labelColor=555555" alt="Full-Stack + DevOps" />
  <img src="https://img.shields.io/badge/Infra-Docker%20%C2%B7%20Jenkins%20%C2%B7%20Cloudflare-0D1117?style=for-the-badge&labelColor=555555" alt="Infrastructure" />
</p>

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=600&size=20&pause=800&color=F0F6FC&center=true&vCenter=true&width=760&lines=Full-Stack+%2F+DevOps+Developer;Enterprise+ERP+%26+CRM+Systems;React+%2B+TypeScript+on+the+Frontend;Java+Spring+Boot+%2B+Python+FastAPI;PostgreSQL+%2B+Redis+%2B+Kafka;Docker+%2B+Jenkins+%2B+Cloudflare;Clean+Architecture+%2B+Database+Design" alt="Typing SVG" />

</div>

---

## О себе

Я **Full-Stack / DevOps Developer** — проектирую и веду системы целиком: от frontend-архитектуры и API до модели данных и production-инфраструктуры. Специализация — внутренние ERP/CRM-системы для бизнеса.

Люблю, когда за фичей стоит чистая архитектура: типизированные контракты между фронтом и бэком, надёжная модель данных, автоматизация бизнес-процессов, server-side генерация документов и DevOps, на котором всё это стабильно живёт.

В мае 2026 завершил ключевой этап системы для **MVP Volleyball Academy** и присоединился к **ТОО «GMS Construction»**, где веду ERP для крупной строительной компании: отвечаю за frontend-архитектуру, backend и разделяю DevOps/инфраструктуру.

---

## Технологический стек

<div align="center">
<table>
  <tr>
    <td align="center" width="20%"><b>Languages</b><br><br><img src="https://skillicons.dev/icons?i=python,java,ts" alt="Languages" /></td>
    <td align="center" width="20%"><b>Backend</b><br><br><img src="https://skillicons.dev/icons?i=fastapi,spring,django" alt="Backend" /></td>
    <td align="center" width="20%"><b>Data</b><br><br><img src="https://skillicons.dev/icons?i=postgres,redis,kafka" alt="Data" /></td>
  </tr>
  <tr>
    <td align="center" width="20%"><b>Frontend</b><br><br><img src="https://skillicons.dev/icons?i=react,vue,nuxtjs,tailwind" alt="Frontend" /></td>
    <td align="center" width="20%"><b>Infrastructure</b><br><br><img src="https://skillicons.dev/icons?i=docker,jenkins,nginx,cloudflare" alt="Infrastructure" /></td>
    <td align="center" width="20%"><b>Tools</b><br><br><img src="https://skillicons.dev/icons?i=grafana,postman,firebase,git,github" alt="Tools" /></td>
  </tr>
</table>
</div>

---

## Опыт

**ТОО «GMS Construction» — Full-Stack / DevOps Developer** · `Май 2026 — н.в.`

<details>
<summary>Enterprise ERP для строительной компании — продукт + инфраструктура</summary>
<br>

- **Enterprise ERP (React 19 + FastAPI):** участие в разработке внутренней ERP — HR, снабжение, сметы, контроль стройки, документооборот.
- **Frontend Architecture:** типизированный API из OpenAPI-схем, server-state на TanStack Query, route-level RBAC, дизайн-система, realtime-слой на WebSocket.
- **Telegram Mini Apps:** мобильные клиенты на React + Telegram WebApp — единый auth-шлюз и складские операции.
- **DevOps & CI/CD:** перевод стека на Docker Compose, пайплайны Jenkins для авто-деплоя, два окружения (dev / prod), публикация через Cloudflare Tunnel.
- **Infrastructure:** объектное хранилище S3/MinIO, конвертация DOCX→PDF через Gotenberg, локальный AI-инференс (Ollama), nginx-gateway, управление секретами.
- **Backend & Data:** участие в моносервисной (hexagonal) архитектуре, модель данных PostgreSQL, server-side генерация документов.

</details>

**MVP Volleyball Academy — Backend / DevOps Developer** · `2026 — Май 2026`

<details>
<summary>SSOT-архитектура, синхронизация данных, конкурентность</summary>
<br>

- **SSOT Architecture:** синхронизация Google Sheets API ↔ PostgreSQL с единым источником истины.
- **Primary Key Mapping:** MVP ID для стабильной связи игроков, платежей и посещений.
- **Shadow Profiles:** учёт игроков без мобильного приложения — полное покрытие финансового учёта.
- **Concurrency Control:** решение race conditions через распределённые блокировки (Redis Mutex / Redlock).
- **Data Cleansing:** fuzzy matching и транслитерация для миграции и нормализации legacy-данных.
- **Background Jobs & DevOps:** очереди, асинхронная обработка, деплой и production-окружение на Heroku.

</details>

**АРРФР — Full-Stack Developer** · `2024 — 2025`

<details>
<summary>CRM + Helpdesk на Django / Nuxt.js, real-time, интеграции</summary>
<br>

- **CRM-система:** full-stack решение (Django + Nuxt.js) для анализа финансовой грамотности 10 000+ пользователей.
- **Helpdesk:** тикет-система с real-time уведомлениями через WebSockets и Kafka.
- **Process Optimization:** −40% времени обработки заявок за счёт автоматизации и аналитических дашбордов.
- **Frontend & UI/UX:** редизайн сайта агентства (TypeScript, Tailwind, SSR на Nuxt.js).
- **Integrations:** Telegram Bot API для автоматизированного сбора данных.

</details>

---

## Что я проектирую и запускаю

<div align="center">
<table>
  <tr>
    <td align="center"><b>Frontend Architecture</b><br><sub>React · typed API · RBAC</sub></td>
    <td align="center"><b>Backend API</b><br><sub>REST · validation · service layer</sub></td>
    <td align="center"><b>Database Schema</b><br><sub>PostgreSQL · FK · migrations</sub></td>
  </tr>
  <tr>
    <td align="center"><b>ERP / CRM Modules</b><br><sub>internal business systems</sub></td>
    <td align="center"><b>Business Workflows</b><br><sub>statuses · approvals · audit trail</sub></td>
    <td align="center"><b>Document Generation</b><br><sub>DOCX templates · PDF archive</sub></td>
  </tr>
  <tr>
    <td align="center"><b>CI/CD & Deploy</b><br><sub>Docker · Jenkins · dev/prod</sub></td>
    <td align="center"><b>Infrastructure</b><br><sub>Cloudflare · S3/MinIO · Nginx</sub></td>
    <td align="center"><b>Monitoring</b><br><sub>logs · metrics · Grafana</sub></td>
  </tr>
</table>
</div>

---

## GitHub Statistics

<div align="center">

<img src="https://streak-stats.demolab.com?user=LINESKL&theme=github-dark-blue&hide_border=true&background=0D1117&stroke=30363D&ring=58A6FF&fire=58A6FF&currStreakLabel=F0F6FC&sideLabels=8B949E&dates=8B949E" alt="GitHub Streak" />

</div>

---

## Контакты

<div align="center">

<b>Открыт к нетворкингу, техническим консультациям и интересным full-stack / DevOps-проектам</b>

<p>
  <a href="https://t.me/lineskl"><img src="https://img.shields.io/badge/Telegram-@lineskl-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" /></a>
  <a href="mailto:lineskl.aliar@gmail.com"><img src="https://img.shields.io/badge/Gmail-write%20me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" /></a>
</p>

<sub>«Тони Старк собрал мини-реактор, сидя в яме… Чем я хуже?» — SNOWNUMB</sub>

</div>
