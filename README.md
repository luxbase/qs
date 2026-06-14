# Qualis Studio

> Transform any visual into its best version.

**Qualis Studio** is a premium visual transformation service — digital staging, photo enhancement, and visual content powered by AI. Optimized for the Paraguayan market, trilingual (ES/EN/PT).

## Stack

| Capa | Tecnología |
| :--- | :--- |
| **Framework** | [Astro](https://astro.build/) (static) |
| **Hosting** | GitHub Pages (`luxbase/qs`) |
| **Formulario** | SubmitKit |
| **Idiomas** | Español, English, Português |

## Estructura

```
/src
  /i18n        # ES/EN/PT dictionaries
  /components  # Hero, Comparison, FAQ, ContactModal, etc.
  /layouts     # Layout base + OG/Twitter/JSON-LD
  /pages       # [lang]/, privacidad, gracias
  constants.ts # WhatsApp number
```

## Desarrollo

```bash
npm install
npm run dev      # localhost
npm run build    # → dist/
npm test         # = astro build (CI check)
```