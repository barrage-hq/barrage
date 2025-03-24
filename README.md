# Barrage

**Barrage** is an open-source, reliable callback delivery service. It acts as a central hub that receives events from multiple sources (HTTP, queues, etc.) and routes them to multiple destinations with retry logic, backoff, observability, and traceability.

> **Status:** Actively in development – not production-ready yet.

---

## ✨ Why Temporal?

**Barrage** is built on top of [Temporal](https://temporal.io), a powerful and reliable workflow orchestration engine.

### Why we chose Temporal:

- ⚙️ **Built-in resilience** – retries, timers, and backoff are first-class features
- 💡 **Declarative modeling for complex logic** – ideal for multi-step workflows
- 🧱 **Durable state and native idempotency** – prevents duplicates and race conditions
- 🛠️ **Mature tooling and extensibility**, especially with the Go SDK

We recognize that Temporal can be seen as a heavyweight dependency. This choice was made with reliability in mind. We're committed to keeping Barrage **modular and loosely coupled**, making it possible to evolve or swap out the orchestration engine in the future.

---

## 🚧 Project Goals

- Receive callbacks via HTTP and messaging systems (SQS, Kafka, etc.)
- Route to multiple targets with fault-tolerance and retry logic
- Provide tenant isolation, security, and traceability
- Offer a clean, simple interface for integration
- Become a robust open-source alternative to in-house callback dispatchers

---

## 🔜 Initial Roadmap

- [ ] Architecture draft
- [ ] Temporal-powered dispatcher prototype
- [ ] HTTP Source and HTTP Sink support
- [ ] Retry mechanism with exponential backoff
- [ ] Observability (logs + metrics)

---

## 🛡️ License

Distributed under the [MIT License](./LICENSE).

---

## 🤝 Contributing

Want to contribute, test, or provide feedback? A contributing guide will be available soon. In the meantime, feel free to open issues or discussions.

---

## 📫 Contact

Project maintained by [@barrage-hq](https://github.com/barrage-hq).
