# Денис Олейник — nedlosster

Principal Architect / Staff Engineer. 25 лет в разработке ПО с 2001 года (МГТУ им. Баумана, ИУ-5).

Проектирую и эксплуатирую распределённые системы и облачные платформы для регулируемых отраслей
с изолированным контуром (air-gap). Последние два года строю инфраструктуру локального
AI-инференса. Беру разные роли в зависимости от масштаба: ведущий разработчик, технический лидер
(tech lead), руководитель группы (team lead), DevOps-инженер, архитектор.

## Чем занимаюсь сейчас

- Облачная платформа как IaC для Kubernetes, PostgreSQL и compute (Go, Python, Terraform, Ansible).
  Гексагональная архитектура (ports & adapters), доменные спецификации, зеркальные профили
  (mirror profiles) для изолированного контура.
- Сервер локального inference для LLM в закрытом контуре: AMD Strix Halo с unified memory 120 GiB,
  llama.cpp, квантование, работа без облачных сервисов.
- Configuration Management Database с мульти-мастерной репликацией между ЦОД и битемпоральным
  учётом (valid_time + transaction_time).

## Карьерные эпохи

- 2001-2014 — телеком-домен: биллинг, маршрутизация, статистика и аналитика.
- 2014-2024 — JVM и функциональное программирование: Scala (Typelevel stack), Akka, Kafka Streams,
  Cassandra; event-driven, Lambda/Kappa, CQRS.
- 2024-2025 — облачные платформы: Go, Python, KVM, Kubernetes, Terraform.
- 2026 — AI-инфраструктура локального инференса.

## Навыки по слоям

- Распределённые системы: битемпоральные модели данных, multi-master репликация, Raft,
  eventual consistency.
- Архитектура: hexagonal (ports & adapters), DDD, ADR-driven design, specification pattern,
  C4-моделирование, миграция 24x7 через паттерн «Душитель» (strangler).
- Stream processing: Kafka Streams, Spark, event-sourcing, CQRS, BPMN-оркестраторы (Camunda, Zeebe).
- Инфраструктура: Kubernetes (on-premise), KVM/QEMU, Terraform, Ansible,
  PostgreSQL (HA, streaming replication).
- SRE: chaos engineering, SLI/SLO/SLA, error budget, DORA-метрики;
  мониторинг — Prometheus, Grafana, ELK, Graylog.
- AI-инфраструктура: внутреннее устройство llama.cpp, KV-cache, компромиссы квантования,
  локальный inference в изолированном контуре.
- Языки: Scala (эксперт, FP/Typelevel), Java, C++, Python, Go, TypeScript.

## Методологии

- AI_CLOSED_LOOP_METHODOLOGY — практика применения LLM в изолированном контуре.
- AI_DEVELOPMENT_METHODOLOGY — эмпирический анализ ROI разработки с AI на реальных git-метриках.

## Образование

МГТУ им. Баумана, ИУ-5, выпуск 2001.

## Контакты

- Почта: nedlo@yandex.ru
- [Книги, которые сформировали меня](Books.md)
