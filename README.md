# Привет, я Илназ! 👋

Бэкенд-разработчик и студент кафедры **Прикладной математики КФУ**. 
Выпускник **Школы 21**.

Специализируюсь на Python-разработке высоконагруженных систем автоматизации и интеграции. Умею проектировать распределенную инфраструктуру и работать с большими массивами данных в Enterprise-сегменте.

---

## 🛠 Технические кейсы (Practical Experience)

Здесь представлены наиболее сложные задачи из моей практики:

*   **Распределенный кластер синхронизации (High-Load):** Построение отказоустойчивой системы обмена данными между VK и облачным Битрикс24 (**100k+ сущностей в сутки**).
    *   *Архитектура:* Кластер из **4 независимых серверов** с распределенной очередью задач.
    *   *Решение Throttling:* Использование **Redis** как единого брокера состояний и воркеров для координации запросов. Это позволило эффективно обходить лимиты REST API (2 req/sec) и распределять нагрузку между узлами.
    *   *Надежность:* Централизованный мониторинг ошибок в БД и автоматическая система Retry-запросов при сбоях.

*   **Масштабная миграция данных (ETL):** Проектирование и реализация миграции более **1 000 000 объектов** из Wrike в Битрикс24. 
    *   *Объем:* Проекты, задачи, комментарии, файлы, структура пользователей.
    *   *Сложность:* Полное сохранение реляционных связей (User Mapping) и иерархии сущностей. Оптимизация скриптов переноса для обеспечения минимального времени простоя системы.

---

## 🚀 Избранные проекты (Showcase)

| Проект | Стек и архитектура |
| :---: | :--- |
| <img src="https://img.icons8.com/fluency/160/calculator.png" width="160" alt="Smart Engine"> | **[Bitrix24 Smart Engine](https://github.com/Imanbe/bitrix-smart-engine)**<br>![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)<br><br>Инструмент для высоконагруженной автоматизации CRM. Позволяет обрабатывать массивы данных (10k+ элементов), используя распределенные блокировки (Redis Locks) и асинхронные воркеры. |
| <img src="https://img.icons8.com/fluency/160/chat-message.png" width="160" alt="Chat App"> | **[FastAPI Real-time Chat](https://github.com/Imanbe/fastapi-chat-app)**<br>![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![WebSockets](https://img.shields.io/badge/-WebSockets-010101?style=flat-square&logo=socket.io&logoColor=white)<br><br>Реализация двусторонней связи в реальном времени с использованием асинхронных протоколов и WebSockets. |

---

## 🛠 Технический стек

### Языки и Инструментарий
- **Languages:** Python (2 года), C# (Middle), C/C++ (Base)
- **Integrations:** Bitrix24 REST API, VK Ads API, Wrike API, Senler, Telegram (Aiogram/Telethon)
- **Backend:** FastAPI, PostgreSQL, SQLAlchemy, Alembic
- **Distributed:** Redis (Locks/Streams/Pub-Sub), ARQ, Celery

### Профессиональные навыки
- Проектирование сложных моделей данных и CRM-автоматизаций.
- Построение отказоустойчивых интеграций с внешними API.
- Настройка мониторинга и логирования (Grafana, Prometheus).

---

## 📊 Статистика кода

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Imanbe&show_icons=true&theme=tokyonight&count_private=true&hide_border=true" width="400" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Imanbe&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" width="300" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Imanbe&theme=tokyonight&hide_border=true" width="710" />
</p>

---

## 📫 Контакты

- **Telegram:** [@ilnazik_kik](https://t.me/ilnazik_kik)
- **Email:** ilnazlive@gmail.com

---
*«Совмещаю опыт бизнес-аналитики с программирование для конструирования надежных систем (стараюсь).»*
