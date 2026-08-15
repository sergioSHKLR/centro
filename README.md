# centro

**Demo Center** — instance + (optional) GitHub Pages host for an adhered Centro.

| | |
|--|--|
| **Role** | Sample `center-*` style repo: brand + manual source; Pages/CNAME when you enable them |
| **Shell** | [`librus-shell`](https://github.com/sergioSHKLR/librus-shell) |
| **Shared books** | [`doutrina-content`](https://github.com/sergioSHKLR/doutrina-content) → [`librus-linker`](https://github.com/sergioSHKLR/librus-linker) |
| **Sibling hosts** | [`librus`](https://github.com/sergioSHKLR/librus) · [`doutrina`](https://github.com/sergioSHKLR/doutrina) |

## Contents

| Path | Purpose |
|------|---------|
| `flavor.json` | Center identity, hosts, providers, JaaS **UI** flag (BYO 8x8 — no secrets here) |
| `manual/` | Student manual (Markdown + front matter) |
| `assets/` | Mark / icons for this Center |

Application source does **not** live here. Until CI assembles `librus-shell` + this content into `dist/`, enable Pages on a simple placeholder or after first deploy pipeline.

## Adhesion (product intent)

| URL | Meaning |
|-----|---------|
| `doutrina.org` | Shared shelf, no video conf |
| `*.doutrina.org` / this demo host | Named Center + optional conf (BYO JaaS) |
| Own domain | CNAME here when adhered |

## Pages / CNAME (you)

1. Settings → Pages → source as you prefer (Actions or branch).
2. Custom domain / CNAME for your demo hostname.
3. Do not commit JaaS signing secrets; only public `appId` / room / your token URL.

## Repo map

| Repo | Role |
|------|------|
| librus-shell | SPA |
| librus-linker | Link injection |
| doutrina-content | Editorial books |
| librus / doutrina / **centro** | Hosts / demo instance |
