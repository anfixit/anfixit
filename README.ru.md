<div align="center">

# Анфиса Ковганюк

### SRE / DevOps-инженер · Инженер инфраструктуры и сетей · Автоматизация на Python

Строю, защищаю и автоматизирую инфраструктуру, которая должна стабильно работать в production.

[![English version](https://img.shields.io/badge/English_version-README.md-0A66C2?style=flat-square)](README.md)
[![Telegram](https://img.shields.io/badge/Telegram-@Anfikus-26A5E4?style=flat-square&logo=telegram&logoColor=white)](https://t.me/Anfikus)
[![Email](https://img.shields.io/badge/Email-anfisa.kovganyuk%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:anfisa.kovganyuk@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-anfixit-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/anfixit)

Тольятти · Рассматриваю удалённый и гибридный формат · Английский B2 · Русский родной

</div>

---

## Обо мне

Работаю на пересечении производственной IT-инфраструктуры, сетевой инженерии, инфраструктурной безопасности и программной автоматизации.

Мой опыт объединяет практическое администрирование Windows и Linux, Active Directory, VMware, управляемых сетей, VPN-платформ, мониторинга и устранения инцидентов с backend-разработкой на Python, автоматизацией на Bash, Docker и CI/CD.

Особенно сильна в задачах, где инфраструктуру нужно сделать повторяемой, наблюдаемой, безопасной и хорошо документированной.

**Целевые позиции:** SRE, DevOps-инженер, инженер по эксплуатации и сопровождению инфраструктуры, инженер по автоматизации инфраструктуры.

## Результаты в цифрах

| Направление | Результат |
| --- | --- |
| Производственная IT-инфраструктура | Сопровождаю среду примерно на **50 пользователей**: **2 физических сервера Dell**, VMware, **15 управляемых коммутаторов HP**, корпоративную Wi-Fi-сеть, Windows и Linux |
| Распределённая инфраструктура | Построила и эксплуатирую коммерческую production VPN-платформу: **25 Linux-серверов**, **20 VPN-нод в 7 странах** у 12 хостеров, около **110 учётных записей**, 130-186 ГБ трафика в сутки |
| Надёжность | **99,93% средней доступности нод** по данным Prometheus и blackbox_exporter, ни одного полного отказа сервиса, включая поочерёдную перезагрузку 11 нод и обновления ПО |
| Балансировка | Спроектировала балансировку по странам с health-check: **28 серверных записей свернула в 14** с автовыбором самого быстрого живого узла, раскатка поэтапная, со сценарием отката |
| Наблюдаемость | Мониторинг **37 целей** на Prometheus, Grafana, Alertmanager и blackbox, алерты в Telegram по уровням срочности и правило, которое ловит отказ самого мониторинга |
| Автоматизация | Сократила ввод новой ноды примерно с **30 до 5 минут** идемпотентным Bash-инструментом; автоматизировала исправление продления TLS-сертификатов, которое тихо падало на **9 из 14 нод** |
| Продуктовая разработка | Разработала личный кабинет с приёмом платежей (FastAPI, React, PostgreSQL, **500+ тестов**, CI/CD) и **AI-агента поддержки** на LLM для Telegram и MAX с инструментами и консолью оператора |
| Реакция на инциденты | Во время крупного инфраструктурного сбоя восстановила Wi-Fi за **21 минуту**, полное восстановление заняло около **2 часов 20 минут** |
| Python-разработка | Написала и доработала около **70 автоматических тестов**, автоматизация регулярных операций сократила время выполнения примерно на **30-40%** |

## Карта компетенций

### Практический production-опыт

- **Системы и управление доступом:** Windows, Ubuntu Server, Linux, Active Directory, пользователи, группы, права доступа и операции, связанные с GPO
- **Сети:** TCP/IP, подсети, LAN, VLAN, маршрутизация, NAT, Wi-Fi, VPN, DNS, управляемые коммутаторы HP и анализ трафика в Wireshark
- **Виртуализация и эксплуатация:** VMware, контроль серверной и ИБП, диагностика инцидентов, восстановление сервисов и техническая документация
- **Безопасность:** SSH только по ключам, UFW, fail2ban, автоматизация TLS-сертификатов Let's Encrypt, Nginx и Caddy, принцип наименьших привилегий и безопасная работа с секретами
- **Контейнеры и доставка:** Docker, Docker Compose, GitHub Actions, версионированные образы, health checks, smoke-проверки, деплой и откат
- **Наблюдаемость:** SolarWinds, Prometheus, Grafana, Alertmanager, node_exporter, blackbox_exporter, журналы, алерты по уровням срочности и анализ доступности
- **Разработка и данные:** Python, Bash, FastAPI, Django, REST API, PostgreSQL, SQLAlchemy, Redis, pytest, React и TypeScript

### Архитектурные знания и диагностика

- Windows Event Logs и аудит, диагностика RDP, application control, делегирование в AD, LAPS и разделение привилегированных учётных записей
- Linux-журналы journald, rsyslog и auditd, пакетные менеджеры, SSSD, Kerberos и LDAP
- Изоляция и безопасность контейнеров: namespaces, cgroups, capabilities, seccomp, rootless-контейнеры и риски Docker socket
- High availability, балансировка, health checks, connection draining, тестирование failover и поиск single point of failure
- Резервное копирование, тесты восстановления, immutable-копии, retention, RTO/RPO, различия snapshot, replication и backup
- Резервирование PostgreSQL и MySQL, WAL и binary logs, репликация, connection pooling и концепции кластеров и failover
- Безопасность CI/CD, GitHub Secrets, защищённые environments, concurrency, readiness/liveness и стратегия отката

## Технологический стек

### Инфраструктура и безопасность

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Ubuntu](https://img.shields.io/badge/Ubuntu_Server-E95420?style=flat-square&logo=ubuntu&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D4?style=flat-square&logo=windows&logoColor=white)
![Active Directory](https://img.shields.io/badge/Active_Directory-0078D4?style=flat-square&logo=microsoft&logoColor=white)
![VMware](https://img.shields.io/badge/VMware-607078?style=flat-square&logo=vmware&logoColor=white)
![Networking](https://img.shields.io/badge/TCP%2FIP_VLAN_VPN-005571?style=flat-square)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Caddy](https://img.shields.io/badge/Caddy-1F88C0?style=flat-square&logo=caddy&logoColor=white)

### Автоматизация, доставка и наблюдаемость

![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Alertmanager](https://img.shields.io/badge/Alertmanager-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

### Backend и данные

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

## Избранные проекты

| Проект | Что демонстрирует |
| --- | --- |
| **[VPaNfi](https://github.com/anfixit/vpanfi)** | Личный кабинет моего коммерческого VPN-сервиса: асинхронный backend на FastAPI, frontend на React и TypeScript, PostgreSQL, Redis, JWT и вход через OAuth, интеграция эквайринга с идемпотентными вебхуками, транзакционная почта, триал и реферальная программа, 500+ тестов и CI/CD на GitHub Actions до production. |
| **[routerus](https://github.com/anfixit/routerus)** | Идемпотентное развёртывание VPN-нод Remnawave и Xray-core на Ubuntu 24.04. Хардинг SSH, UFW, fail2ban, автоматизация Let's Encrypt с самопочинкой продления, Nginx, защита секретов, логирование, watchdog, настройка транспортов TCP/XHTTP, регистрация ноды в панели через API и скрипт самопроверки. |
| **[router-provisioner](https://github.com/anfixit/router-provisioner)** | Настройка OpenWrt-роутера одной командой: VPN-подписка на sing-box, split-tunneling, блокировка рекламы через DNS. Резервная копия перед изменениями, идемпотентный повторный запуск, режимы dry-run и diagnose, сторожевой сервис, который не оставит роутер без интернета, ночные обновления с автооткатом. |
| **[anfinances](https://github.com/anfixit/anfinances)** | Self-hosted система личных финансов с мультивалютностью, доменным async backend на FastAPI, типизированным frontend на React, PostgreSQL, YNAB-бюджетами, backup/restore, тестами и production-деплоем в Docker. |
| **[unpaywallbot](https://github.com/anfixit/unpaywallbot)** | Исследовательский проект по информационной безопасности, демонстрирующий недостатки клиентских механизмов контроля доступа. Модульная обработка данных, шифрование сессий, Redis, rate limiting, аудит, автоматические тесты, проверка зависимостей и контейнеризированный CI/CD. |
| **[voice_match](https://github.com/anfixit/voice_match)** | Система конфиденциального локального анализа сходства голосов на основе нескольких аудиомоделей и эмбеддингов. Обработка выполняется без облачных API, временные файлы удаляются, поддерживается самостоятельное развёртывание через Docker. |
| **[Python Engineering Handbook](https://github.com/anfixit/vibe-python-engineering-handbook)** | Open-source справочник по production-разработке на Python: архитектура, безопасность, типизация, async, FastAPI, Django, тестирование, Docker, CI/CD, деплой и мониторинг. |

Дополнительные проекты: [auth_project](https://github.com/anfixit/auth_project), [simoronator](https://github.com/anfixit/simoronator), [naspch_bot](https://github.com/anfixit/naspch_bot), [freelance_lena_bot](https://github.com/anfixit/freelance_lena_bot).

## Опыт

### AD Plastik Togliatti · Специалист-техник по компьютерным сетям и системам
**Сентябрь 2025 - настоящее время**

Производственная IT-инфраструктура примерно на 50 пользователей: Windows и Linux, Active Directory, VMware, серверы Dell, управляемые коммутаторы HP, корпоративная Wi-Fi-сеть, VPN, мониторинг SolarWinds, устранение инцидентов и координация с центральной IT-командой в Хорватии.

### Проектная деятельность · инфраструктура, SRE и Python-разработка
**Декабрь 2024 - настоящее время**

Проектирование, развёртывание и эксплуатация коммерческой VPN-платформы: 25 Linux-серверов, 20 нод в 7 странах, измеренная доступность нод 99,93%. Ubuntu Server, Docker, Xray-core, Remnawave, Nginx, Caddy, Let's Encrypt, UFW, fail2ban, балансировка по странам, Prometheus, Grafana, Alertmanager, бэкапы, расследование инцидентов, автоматизация на Bash/Python и GitHub Actions. Личный кабинет с приёмом платежей (FastAPI, React, PostgreSQL) и AI-агент поддержки на LLM. Второй коммерческий проект: настройка OpenWrt-роутеров с VPN-подпиской.

### AL YWIN, Прага · Python-разработчик и инженер по автоматизации
**Сентябрь 2024 - сентябрь 2025**

Backend-разработка на Python и Django, PostgreSQL, REST API, автоматизация обработки данных, исключения, валидация, логирование, автоматические тесты, рефакторинг и тестовое окружение в Docker в составе кросс-функциональной продуктовой команды.

## Образование и подтверждённые компетенции

- **Прикладная информатика**, Технологии разработки программного обеспечения, Московский технологический институт, 2020
- **Python-разработчик. Расширенный**, Яндекс Практикум, 612 часов, 2025
- **System Analysis**, ASTON, 2025
- **Cisco Networking Academy**, программы CCNA и CCNP, 2015
- **Национальная система оценки IT-компетенций, 2026:**
  - API, Docker, Git, Linux и PostgreSQL: продвинутый теоретический уровень
  - Python: средний уровень теории и практики

## GitHub-активность

<!-- Карточки автоматически создаются workflow .github/workflows/profile-cards.yml -->

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="profile-summary-card-output/github_dark/0-profile-details.svg">
  <source media="(prefers-color-scheme: light)" srcset="profile-summary-card-output/github/0-profile-details.svg">
  <img width="100%" alt="GitHub profile details" src="profile-summary-card-output/github/0-profile-details.svg">
</picture>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="profile-summary-card-output/github_dark/1-repos-per-language.svg">
    <source media="(prefers-color-scheme: light)" srcset="profile-summary-card-output/github/1-repos-per-language.svg">
    <img width="49%" alt="Repositories per language" src="profile-summary-card-output/github/1-repos-per-language.svg">
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="profile-summary-card-output/github_dark/3-stats.svg">
    <source media="(prefers-color-scheme: light)" srcset="profile-summary-card-output/github/3-stats.svg">
    <img width="49%" alt="GitHub statistics" src="profile-summary-card-output/github/3-stats.svg">
  </picture>
</p>

---

<div align="center">

**Инфраструктура должна быть понятной, воспроизводимой и восстанавливаемой.**

[Telegram](https://t.me/Anfikus) · [Email](mailto:anfisa.kovganyuk@gmail.com) · [GitHub](https://github.com/anfixit)

</div>
