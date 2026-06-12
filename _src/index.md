---
layout: home

hero:
  name: Middenly
  text: Build reliable distributed systems
  tagline: Production-ready .NET libraries for Event Sourcing, CQRS, and Event-Driven architectures.
  actions:
    - theme: brand
      text: Get Started
      link: /outbox/guide/outbox-pattern
    - theme: alt
      text: GitHub
      link: https://github.com/Middenly/Middenly

features:
  - icon: 📦
    title: Transactional Outbox
    details: Store messages in PostgreSQL alongside your business data. Avoid dual-write problems entirely.
    link: /outbox/guide/outbox-pattern
  - icon: ⚡
    title: Confluent.Kafka Native
    details: First-class Kafka producer with headers, keys, partitions, and all producer configuration options.
    link: /outbox/guide/kafka
  - icon: 🔄
    title: Automatic Retry & Dead Letter
    details: Configurable retry policies with automatic dead letter queue support for failed messages.
    link: /outbox/guide/dead-letter
  - icon: 🔒
    title: Multi-Instance Safe
    details: FOR UPDATE SKIP LOCKED for safe concurrent access. Stuck message recovery after crashes.
    link: /outbox/guide/postgresql
  - icon: 🗄️
    title: EF Core Integration
    details: Atomic SaveChanges with UseEfCoreOutbox. Messages stored in the same transaction as your data.
    link: /outbox/guide/efcore
  - icon: ⚙️
    title: Per-Topic Configuration
    details: Fluent API for ordering, retries, and delivery options per destination.
    link: /outbox/guide/topic-configuration
---
