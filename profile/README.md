# gnas.dev

**Personal tools for the AI era.**

Self-built, self-run, self-improved — AI as the lever, humans at the wheel.

Solo developer · Ho Chi Minh City · [gnas.dev](https://gnas.dev) · [Facebook](https://www.facebook.com/gnasdev)

---

## Live products

| Product | What it is | Link |
|--------|------------|------|
| **GN Shop** | Fashion store we host | [shop.gnas.dev](https://shop.gnas.dev) |
| **GN Money** | Personal spending ledger | [money.gnas.dev](https://money.gnas.dev) |
| **GN Engreel** | Daily vocabulary practice | [engreel.gnas.dev](https://engreel.gnas.dev) |

## Open source

| Project | What it is | Link |
|---------|------------|------|
| **GN Drive** | Desktop cloud sync (rclone + Wails) | [github.com/gnasdev/gn-drive](https://github.com/gnasdev/gn-drive) |
| **GN Tracing** | Browser debug / session tools | [github.com/gnasdev/gn-tracing](https://github.com/gnasdev/gn-tracing) |

## Platform (monorepo)

Active development lives in a single private monorepo (`infra`):

| Surface | Notes |
|---------|--------|
| **Apps** | `gn-shop`, `gn-money`, `gn-engreel`, `gn-cad` (+ shared `gn-backend-shared`, `gn-ui-shared`) |
| **Sites** | [gnas.dev](https://gnas.dev) landing · [sang.id.vn](https://sang.id.vn) blog |
| **Runtime** | Docker Compose on a home Mac mini · Nginx gateway · Cloudflare Tunnel / DNS / TLS |
| **Frontends** | SolidJS SPAs on **Cloudflare Pages** (`*.gnas.dev`) |
| **APIs** | Go (Gin) · per-app OIDC via shared auth packages · MongoDB · Redis · MinIO |
| **Ops** | Taskfile · SOPS+age secrets · GHCR images · monitoring (VictoriaMetrics, Dozzle) |

Also in progress: **GN CAD** — multi-user parametric CAD workbench (`cad.gnas.dev`).

---

## Principles

- Ship tools we actually use every day
- Self-host what matters; avoid vendor lock-in where it hurts
- Keep the stack understandable by one person end-to-end
- Prefer monorepo + shared libraries over fragmented micro-repos

## Contact

- Web: [https://gnas.dev](https://gnas.dev)
- Email: [ngosangns@gmail.com](mailto:ngosangns@gmail.com)
- Facebook: [facebook.com/gnasdev](https://www.facebook.com/gnasdev)
