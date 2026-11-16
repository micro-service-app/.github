# Multi-ERP

[English](#english) · [Türkçe](#türkçe)

## English

An open source ERP built as a playground for **micro frontends** and **polyglot microservices**: every part is written in a different language or framework, lives in its own repository, and still feels like one application.

- **Micro frontends** composed on the server with PuzzleJS: Web components, React, Vue 3, Svelte and Angular.
- **Microservices** in Go, Java / Spring Boot, C# / .NET, Python / FastAPI and Node.js, talking through **RabbitMQ** events.
- **Workspaces**: every visitor gets an isolated workspace with sample data, identified by a code.
- **Invoice designer**: drag-and-drop UBL-TR invoice templates, import and visually edit GİB XSLT templates, PDF and e-mail.
- **Deployment** with Docker Compose or Kubernetes.

Start with **[platform](https://github.com/micro-service-app/platform)**: it explains the architecture and starts everything with `make clone && make up`.

## Türkçe

**Micro frontend** ve **çok dilli mikroservis** mimarisini denemek için yazılmış açık kaynak bir ERP. Her parça farklı bir dil ya da çatıyla yazıldı, kendi reposunda duruyor ve yine de tek bir uygulama gibi çalışıyor.

- PuzzleJS ile sunucuda birleştirilen **micro frontend'ler**: Web bileşenleri, React, Vue 3, Svelte ve Angular.
- Go, Java / Spring Boot, C# / .NET, Python / FastAPI ve Node.js ile yazılmış, **RabbitMQ** olaylarıyla haberleşen **mikroservisler**.
- **Çalışma alanları**: her ziyaretçi örnek verilerle dolu, kendine ait ve bir kodla açılan bir alan alır.
- **Fatura tasarım aracı**: sürükle-bırak UBL-TR fatura şablonları, GİB XSLT şablonlarını içe aktarıp görsel düzenleme, PDF ve e-posta.
- Docker Compose ya da Kubernetes ile **yayın**.

İşe **[platform](https://github.com/micro-service-app/platform)** reposuyla başlayın: mimariyi anlatır ve `make clone && make up` ile her şeyi ayağa kaldırır.
