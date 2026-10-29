# Awesome Celery with stars

> The Awesome Celery list is a curated collection of open source resources, tools, and libraries for the Python Celery task queue. The list includes libraries and tools to make working with Celery easier, as well as interesting projects and examples. Whether you're new to Celery or an experienced developer, the list has something for everyone.

## Contents

* [General](#general)
* [Administration and Monitoring](#administration-and-monitoring)
* [Analogues](#analogues)
* [Task flow and organization](#task-flow-and-organization)
* [Implementation in different languages](#implementation-in-different-languages)

## General

General Celery related items.

* [Celery GitHub](https://github.com/celery/celery) ⭐ 29,098 | 🐛 742 | 🌐 Python | 📅 2026-10-28 - Celery source code.
* [celery-tasks-checklist](https://github.com/vintasoftware/celery-tasks-checklist) ⭐ 121 | 🐛 3 | 📅 2019-10-07 - Useful checklist for building great Celery tasks.
* [Celery documentation](https://docs.celeryq.dev/en/stable/) - Documentation on Celery Framework.
* [Celery Pytest Plugin](https://pytest-celery.readthedocs.io) - Official pytest plugin for Celery.

## Administration and Monitoring

* [Flower](https://github.com/mher/flower) ⭐ 7,239 | 🐛 40 | 🌐 Python | 📅 2026-09-22 - Web-based tool for managing and administering Celery clusters.
* [django-celery-beat](https://github.com/celery/django-celery-beat) ⭐ 1,956 | 🐛 156 | 🌐 Python | 📅 2026-10-28 - Running periodic tasks from Django Admin.
* [django-health-check](https://github.com/revsys/django-health-check) ⭐ 1,426 | 🐛 1 | 🌐 Python | 📅 2026-10-28 - Health check plugin for Django. Celery health checks are bundled.
* [django-celery-results](https://github.com/celery/django-celery-results) ⭐ 785 | 🐛 67 | 🌐 Python | 📅 2026-10-21 - Storing task results using the Django ORM.
* [celery-exporter](https://github.com/danihodovic/celery-exporter) ⭐ 566 | 🐛 49 | 🌐 Python | 📅 2026-10-09 - A Prometheus exporter for Celery.
* [celery-mixin](https://github.com/danihodovic/celery-exporter/tree/master/celery-mixin) ⭐ 566 | 🐛 49 | 🌐 Python | 📅 2026-10-09 - Monitoring mixin for Celery. A set of Grafana dashboards and Prometheus rules for Celery.
* [celery-progress](https://github.com/czue/celery-progress) ⭐ 496 | 🐛 19 | 🌐 Python | 📅 2026-10-27 - Download progress bar for Django/Celery.
* [clearly](https://github.com/rsalmei/clearly) ⭐ 411 | 🐛 8 | 🌐 Python | 📅 2022-06-07 - Console worker monitoring/inspecting/debugging.
* [Kanchi](https://github.com/getkanchi/kanchi) ⭐ 220 | 🐛 8 | 🌐 Python | 📅 2026-10-21 - Real-time Celery task monitoring and management system with a modern web UI and WebSocket-powered live updates.
* [Leek](https://github.com/kodless/leek) ⭐ 205 | 🐛 19 | 🌐 TypeScript | 📅 2026-06-16 - Monitoring tool that can monitor multiple brokers with a single container, unlike other tools.
* [Celery Insights](https://github.com/danyi1212/celery-insights) ⭐ 110 | 🐛 6 | 🌐 TypeScript | 📅 2026-10-24 - Realtime monitoring tool for Celery clusters with a modern web UI.

## Analogues

* [RQ](https://github.com/rq/rq) ⭐ 10,698 | 🐛 262 | 🌐 Python | 📅 2026-10-28 - Simple, lightweight, Python library for creating background jobs, and processing them.
* [TaskTiger](https://github.com/closeio/tasktiger) ⭐ 1,469 | 🐛 51 | 🌐 Python | 📅 2026-10-19 - Task management using Redis.
* [WakaQ](https://github.com/wakatime/wakaq) ⭐ 596 | 🐛 0 | 🌐 Python | 📅 2026-05-21 - Minimalistic alternative to Celery.
* [aiotasks](https://github.com/cr0hn/aiotasks) ⭐ 455 | 🐛 4 | 🌐 Python | 📅 2026-09-08 - Celery-like task queue but for asyncronous functions.

## Task flow and organization

* [RedBeat](https://github.com/sibson/redbeat) ⭐ 1,054 | 🐛 43 | 🌐 Python | 📅 2026-10-09 - Celery Beat Scheduler that stores the scheduled tasks and runtime metadata in Redis.
* [celery-once](https://github.com/cameronmaske/celery-once) ⭐ 691 | 🐛 48 | 🌐 Python | 📅 2023-08-29 - Prevent multiple execution of celery tasks.
* [Jobtastic](https://github.com/PolicyStat/jobtastic) ⭐ 645 | 🐛 37 | 🌐 Python | 📅 2026-10-27 - Implement progress, status, caching, error handling with simple wrappers.
* [celery-director](https://github.com/ovh/celery-director) ⭐ 552 | 🐛 17 | 🌐 Python | 📅 2025-04-22 - YAML workflows for Celery tasks and WebUI to run them.
* [Selinon](https://github.com/selinon/selinon) ⭐ 314 | 🐛 21 | 🌐 Python | 📅 2025-03-29 - Advanced flow control with dynamic task scheduling and declarative YAML configs.

## Implementation in different languages

* [gocelery](https://github.com/gocelery/gocelery) ⭐ 2,488 | 🐛 57 | 🌐 Go | 📅 2023-09-12 - Go Client/Server for Celery Distributed Task Queue.
* [Rusty Celery](https://github.com/rusty-celery/rusty-celery) ⭐ 876 | 🐛 62 | 🌐 Rust | 📅 2024-06-17 - Rust implementation.
* [celery.node](https://github.com/actumn/celery.node) ⭐ 305 | 🐛 47 | 🌐 TypeScript | 📅 2024-05-30 - Celery client/worker implementation in Node.js.

Contributions are always welcome! Read the [contribution guidelines](contributing.md) first.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-10-29._
