# codestudiopack

![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-online-brightgreen?logo=github)
![Version](https://img.shields.io/badge/AutoPublisher-v12.0-4ade80)
![License](https://img.shields.io/badge/license-MIT-blue)
![Backup](https://img.shields.io/badge/backup-Google Drive-blue)

> Sitio tipo **Custom** publicado automáticamente con [AutoPublisher v12.0](https://github.com).

## 🌐 Sitio en vivo
**[https://elparivera.github.io/codestudiopack/](https://elparivera.github.io/codestudiopack/)**

## 🗂 Estructura del proyecto
```
codestudiopack/
├── index.html              # Página principal (Custom)
├── 404.html                # Página de error personalizada
├── robots.txt              # Directivas SEO
├── sitemap.xml             # Mapa del sitio
├── .nojekyll               # Build rápido en Pages
├── .gitignore              # Archivos ignorados
├── LICENSE                 # MIT
├── README.md               # Este archivo
└── .github/
    └── workflows/
        ├── backup.yml      # ☁️ Backup semanal → Google Drive
        └── ci.yml          # ✅ Validación automática
```

## 🤖 Workflows CI/CD
| Workflow | Trigger | Descripción |
|----------|---------|-------------|
| `backup.yml` | Domingos 02:00 UTC | ☁️ Backup automático a **Google Drive** |
| `ci.yml` | Push a `main` | Valida HTML, tamaño y estructura |

## 🔐 Secrets requeridos
| Secret | Descripción |
|--------|-------------|
| `RCLONE_CONF` | Credenciales para **Google Drive** |

## 🚀 Actualizar el sitio
```bash
git clone https://github.com/elparivera/codestudiopack.git
cd codestudiopack
# Edita tus archivos...
git add . && git commit -m "✨ Actualización" && git push
```

---
*Generado el 26 de marzo de 2026 con ⚡ AutoPublisher v12.0 · Nebula Edition · © 2025 Wil Rivera*
