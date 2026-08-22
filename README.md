# centro

**Build step 4 of 4** · Publish host for **centro.doutrina.org**

---

## 📑 Table of contents

1. 🇺🇸 [English](#-english--build-step-4-of-4)
   1. 🎯 [Audience](#-audience)
   2. 🗺️ [Pipeline position](#-pipeline-position)
   3. 🌐 [This host](#-this-host)
   4. 📁 [What CI preserves](#-what-ci-preserves)
   5. ⚠️ [Do not hand-edit the SPA](#️-do-not-hand-edit-the-spa)
   6. 🤝 [How to help](#-how-to-help)
2. 🇧🇷 [Português](#-português--etapa-4-de-4)
   1. 🎯 [Público](#-público)
   2. 🗺️ [Posição no pipeline](#-posição-no-pipeline)
   3. 🌐 [Este host](#-este-host)
   4. 📁 [O que o CI preserva](#-o-que-o-ci-preserva)
   5. ⚠️ [Não edite a SPA à mão](#️-não-edite-a-spa-à-mão)
   6. 🤝 [Como ajudar](#-como-ajudar)

---

# 🇺🇸 English — Build step 4 of 4

GitHub Pages **deployment mirror** of `librus-shell` `dist/` for **https://centro.doutrina.org** (flavor `centro`).

## 🎯 Audience

1. Center maintainers (`flavor.json`, manual, instance rules)  
2. Volunteers testing center-specific features (e.g. JaaS when enabled)  
3. Collaborators comparing center vs doutrina.org shelves  

**Not** end-user help text.

## 🗺️ Pipeline position

1. [`doutrina-content`](https://github.com/sergioSHKLR/doutrina-content) — shared works  
2. [`librus-linker`](https://github.com/sergioSHKLR/librus-linker) — links  
3. [`librus-shell`](https://github.com/sergioSHKLR/librus-shell) — SPA (`VITE_FLAVOR=centro`)  
4. **This repo** — live publish + center-owned files  

## 🌐 This host

1. **Site:** [centro.doutrina.org](https://centro.doutrina.org)  
2. **Flavor:** `centro` (codification + pinned center manual)  
3. **UI source:** [`librus-shell`](https://github.com/sergioSHKLR/librus-shell)  

## 📁 What CI preserves

On each shell deploy, these paths are **kept** (not clobbered by `assets/`):

1. `flavor.json`  
2. `manual/`  
3. `instance/`  

SPA owns `assets/` and app entry HTML — do not fight the deploy.

## ⚠️ Do not hand-edit the SPA

1. Reader/chrome bugs → **librus-shell**.  
2. Center policy / manual / instance → files preserved above.  
3. Book prose → **doutrina-content**.  

## 🤝 How to help

1. Review center manual and instance conventions.  
2. Test video / provider gates for the `centro` flavor.  
3. Route generic reader issues to the shell.  
4. Ecosystem map: [`librus` README](https://github.com/sergioSHKLR/librus).  

---

# 🇧🇷 Português — Etapa 4 de 4

Espelho de publicação (GitHub Pages) do `dist/` de `librus-shell` em **https://centro.doutrina.org** (sabor `centro`).

## 🎯 Público

1. Mantenedores de centro (`flavor.json`, manual, instance)  
2. Voluntários que testam recursos do centro (ex.: JaaS)  
3. Colaboradores que comparam centro vs doutrina.org  

**Não** é texto de ajuda ao usuário final.

## 🗺️ Posição no pipeline

1. [`doutrina-content`](https://github.com/sergioSHKLR/doutrina-content) — obras compartilhadas  
2. [`librus-linker`](https://github.com/sergioSHKLR/librus-linker) — ligações  
3. [`librus-shell`](https://github.com/sergioSHKLR/librus-shell) — SPA (`VITE_FLAVOR=centro`)  
4. **Este repo** — publicação + arquivos do centro  

## 🌐 Este host

1. **Site:** [centro.doutrina.org](https://centro.doutrina.org)  
2. **Sabor:** `centro`  
3. **UI:** [`librus-shell`](https://github.com/sergioSHKLR/librus-shell)  

## 📁 O que o CI preserva

1. `flavor.json`  
2. `manual/`  
3. `instance/`  

A SPA dona `assets/` e o HTML de entrada.

## ⚠️ Não edite a SPA à mão

1. Bugs de leitor/chrome → **librus-shell**.  
2. Manual / instance do centro → arquivos preservados acima.  
3. Prosa dos livros → **doutrina-content**.  

## 🤝 Como ajudar

1. Revisar manual e convenções de instance.  
2. Testar portões de vídeo / provedores do sabor `centro`.  
3. Issues genéricas de leitor → shell.  
4. Mapa: [`librus` README](https://github.com/sergioSHKLR/librus).  
