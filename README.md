# clase.
# Sitio estático (GitHub → Vercel)

HTML semántico + CSS en la **raíz** del repo.

## Estructura
/
├─ index.html
├─ styles.css
└─ vercel.json

## Deploy
1) Sube a GitHub:
   git init
   git add .
   git commit -m "init: sitio estático en raíz"
   git branch -M main
   git remote add origin https://github.com/TU_USUARIO/TU_REPO.git
   git push -u origin main

2) Conecta en Vercel:
   - Framework: Other
   - Build Command: (vacío)
   - Output directory: /
   - Deploy

