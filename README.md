<div align="center">

# 🛡️ Xavi Haro Llovera

**Estudiante de ASIR · Aprendiendo ciberseguridad**

Mi blog personal: lo que voy aprendiendo sobre Linux, redes y seguridad.

[![Visitar el blog](https://img.shields.io/badge/Visitar_el_blog-xaviharollovera.github.io-2ea44f?style=for-the-badge)](https://xaviharollovera.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Xavi_Haro_Llovera-0A66C2?style=for-the-badge)](https://www.linkedin.com/in/xavi-haro-llovera-9096b6336/)

[![Publicar blog](https://github.com/xaviharollovera/xaviharollovera.github.io/actions/workflows/hugo.yaml/badge.svg)](https://github.com/xaviharollovera/xaviharollovera.github.io/actions/workflows/hugo.yaml)
![Hugo](https://img.shields.io/badge/Hugo-0.169.0-FF4088?logo=hugo&logoColor=white)
![Tema](https://img.shields.io/badge/Tema-Coder-333333)

</div>

---

## 👋 Sobre el blog

Aquí comparto apuntes y prácticas de mi camino en la ciberseguridad, mientras curso el Ciclo Superior en Administración de Sistemas Informáticos en Red (ASIR) y practico en Hack The Box Academy y TryHackMe.

## 🧰 Con qué está hecho

| Herramienta | Para qué |
|---|---|
| [Hugo](https://gohugo.io/) | Generar la web a partir de archivos Markdown |
| [Hugo Coder](https://github.com/luizdepra/hugo-coder) | El tema visual |
| GitHub Actions | Generar y publicar la web en cada `push` |
| GitHub Pages | Alojar la web |

## 📁 Estructura

```text
.
├── content/        # Páginas y artículos en Markdown
│   └── posts/      # Artículos del blog
├── static/         # Imágenes y favicon
├── themes/         # Tema Hugo Coder (submódulo)
├── .github/        # Publicación automática
└── hugo.toml       # Configuración del sitio
```

## 🚀 Ejecutarlo en local

Hace falta [Hugo extended](https://gohugo.io/installation/).

```bash
git clone --recurse-submodules git@github.com:xaviharollovera/xaviharollovera.github.io.git
cd xaviharollovera.github.io
hugo server -D
```

La web se abre en `http://localhost:1313/`.

## ✍️ Escribir un artículo

```bash
hugo new content posts/nombre-del-articulo.md
```

Cambia `draft = true` por `draft = false` y haz `git push`. La web se publica sola en unos minutos.

---

<div align="center">

Hecho con Hugo y el tema [Hugo Coder](https://github.com/luizdepra/hugo-coder) (licencia MIT).

</div>
