<p align="center">
  <img src="docs/banner.svg" alt="Env Example Patterns banner" width="100%" />
</p>

<h1 align="center">env-example-patterns</h1>

<p align="center">
  <strong>EN</strong> Safe .env.example patterns — no real secrets<br/>
  <strong>PT</strong> Padrões seguros de .env.example — sem segredos reais
</p>

<p align="center">
  <a href="https://github.com/manansbdb/env-example-patterns/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-22c55e?style=for-the-badge" alt="MIT" /></a>
  <img src="https://img.shields.io/badge/lang-EN%20%7C%20PT-3b82f6?style=for-the-badge" alt="EN PT" />
  <img src="https://img.shields.io/badge/topic-dotenv-eab308?style=for-the-badge" alt="dotenv" />
  <a href="#support--apoio"><img src="https://img.shields.io/badge/donate-BTC-f59e0b?style=for-the-badge" alt="Donate BTC" /></a>
</p>

---

## What it does / Para que serve

| English | Português |
|---------|-----------|
| Guidelines and an **example `.env.example`** so teams document config without leaking secrets. | Guidelines e um **exemplo `.env.example`** para documentar config sem vazar segredos. |
| Copy the example, rename to `.env`, fill locally, never commit secrets. | Copia o exemplo, renomeia para `.env`, preenche localmente, nunca commits segredos. |

```mermaid
flowchart LR
  A["📄 .env.example"] --> B["✏️ Copy to .env"]
  B --> C["🔐 Fill secrets locally"]
  C --> D["🚫 Never commit .env"]
  style A fill:#ca8a04,stroke:#a16207,color:#fff
  style B fill:#ea580c,stroke:#c2410c,color:#fff
  style C fill:#2563eb,stroke:#1d4ed8,color:#fff
  style D fill:#dc2626,stroke:#991b1b,color:#fff
```

---

## Install / Instalação

### 1) Clone / Clona

```bash
git clone https://github.com/manansbdb/env-example-patterns.git
cd env-example-patterns
```

### 2) Apply / Aplica

```bash
cp examples/.env.example /path/to/your-project/.env.example
cp guidelines.md /path/to/your-project/docs/env-guidelines.md
# then locally:
cp .env.example .env
# edit .env with real values (keep .env gitignored)
```

### Requirements / Requisitos

- `git`
- Ensure `.env` is in `.gitignore`

---

## Quick start / Início rápido

```bash
git clone https://github.com/manansbdb/env-example-patterns.git
cp env-example-patterns/examples/.env.example ./.env.example
cp .env.example .env
```

---

## Contents / Conteúdos

| Path | Purpose / Função |
|------|------------------|
| `examples/.env.example` | Safe placeholder env file |
| `guidelines.md` | Naming & secrecy rules |
| `SUPPORT.md` | Donations / Doações |

---

## Project layout / Estrutura

```text
env-example-patterns/
├── docs/banner.svg
├── examples/.env.example
├── guidelines.md
├── SUPPORT.md
└── README.md
```

---

## Support / Apoio

Bitcoin donations welcome / Doações em Bitcoin bem-vindas:

```
bc1q0qfnlnxyum9u45stzxe0a7jnhtj4j0usfkqdjw
```

See [SUPPORT.md](./SUPPORT.md).

---

## License / Licença

[MIT](./LICENSE) © 2026 manansbdb
