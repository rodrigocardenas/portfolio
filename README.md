# Rodrigo Cárdenas — Portfolio / CV Online

Sitio de portafolio personal construido con **HTML5 semántico**, **Tailwind CSS** (CDN) y **Alpine.js** (CDN).
Diseño Dark-mode primero, glassmorphism, animaciones CSS y scroll-reveal. Listo para publicar en **GitHub Pages** sin ningún build step.

## Stack
- HTML5 + CSS3 (clases Tailwind utility-first)
- [Tailwind CSS v3](https://tailwindcss.com/) via CDN
- [Alpine.js v3](https://alpinejs.dev/) via CDN
- [Formspree](https://formspree.io/) para el formulario de contacto (sin backend)

## Estructura
```
portfolio/
├── index.html          # Todo el sitio (SPA one-file)
├── assets/
│   └── CV_Rodrigo_Cardenas.pdf   # ← coloca aquí tu CV en PDF
└── README.md
```

## Configuración rápida

1. **CV PDF**: coloca tu CV en `assets/CV_Rodrigo_Cardenas.pdf`
2. **Links reales**: actualiza en `index.html` los `href` de GitHub, LinkedIn, email y WhatsApp
3. **Formspree**: regístrate en [formspree.io](https://formspree.io), crea un form y reemplaza `YOUR_FORM_ID` en el `<form action="...">`
4. **Teléfono**: actualiza el número en la sección Contacto y en el link de WhatsApp

## Deploy en GitHub Pages

```bash
git init
git add .
git commit -m "feat: initial portfolio site"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/portfolio.git
git push -u origin main
```

Luego en el repo → **Settings → Pages → Branch: main / root** → Save.
Tu sitio estará en `https://TU_USUARIO.github.io/portfolio`
