# fluye-web

Website público de Fluye BPM: [fluye.ar](https://fluye.ar)

**Stack:** Astro + Markdown + Cloudflare Pages

## 🚀 Project Structure

```text
/
├── public/
│   ├── favicon.svg        # Waves del logo Fluye
│   └── logo-fluye.svg     # Logo completo
├── src/
│   ├── layouts/
│   │   └── Page.astro     # Layout principal con branding
│   └── pages/
│       └── index.md       # Home page (Markdown)
└── package.json
```

**Content:** Todo el contenido está en Markdown (`src/pages/*.md`)

**Branding:**
- Colores: `#1e4c76`, `#547797`, `#708eac`, `#dbe7f6`
- Tipografía: Sans-serif moderna
- Dark theme con gradientes

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 🚀 Deploy

**Hosting:** Cloudflare Pages

**Auto-deploy:** Push to `main` → deploy automático a fluye.ar

**Preview:** Branches crean preview deployments automáticos

## 📝 Content Updates

Para actualizar contenido del sitio:

1. Editar `src/pages/index.md` (Markdown)
2. Commit y push a `main`
3. Cloudflare Pages deploya automáticamente en ~1 minuto

## 🔗 Links

- **Website:** https://fluye.ar
- **Repo código:** https://github.com/pagano/fluye (SDKs open-source)
- **Documentación técnica:** Ver `fluye-core/design/` (repo privado)
