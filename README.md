# Diario Estoico — 366 Meditaciones PWA

Una Progressive Web App (PWA) basada en *El Diario Estoico* de Ryan Holiday. 366 meditaciones diarias sobre la sabiduría, la perseverancia y el arte de vivir.

## ✦ Características

- **Meditación diaria automática** — Muestra la entrada correspondiente al día actual
- **Navegación completa** — Anterior, siguiente, aleatorio, calendario visual
- **PWA instalable** — Añadir a pantalla de inicio en iPhone/Android con icono personalizado
- **Funciona offline** — Service Worker cachea todos los recursos
- **Gestos táctiles** — Desliza para cambiar de día
- **Compartir** — Comparte meditaciones vía share nativo (iOS/Android)
- **Guardar favoritas** — Sistema de bookmarks con localStorage
- **Optimizado para iPhone** — Safe areas, status bar, viewport-fit

## 📱 Instalación en iPhone

1. Abre la URL en Safari
2. Toca el botón **Compartir** (⬆️)
3. Selecciona **"Añadir a pantalla de inicio"**
4. La app aparecerá con icono propio y se abrirá a pantalla completa

## 🚀 Deploy en GitHub Pages

```bash
# 1. Crear repo en GitHub (nombre: diario-estoico)
git init
git add .
git commit -m "Diario Estoico PWA v1.0"
git branch -M main
git remote add origin https://github.com/jbt777/diario-estoico.git
git push -u origin main

# 2. En GitHub → Settings → Pages → Source: main branch → Save
# 3. URL: https://jbt777.github.io/diario-estoico/
```

## 📂 Estructura

```
diario-estoico/
├── index.html          # App principal
├── entries.js          # 366 meditaciones (datos)
├── manifest.json       # PWA manifest
├── sw.js              # Service Worker (offline)
├── apple-touch-icon.png
├── icons/
│   ├── icon-192x192.png
│   └── icon-512x512.png
└── README.md
```

## 🎨 Diseño

- **Estética**: Oscura, clásica, tipografía serif (Cinzel + EB Garamond + Cormorant Garamond)
- **Paleta**: Negro (#0d0b09) + Oro (#c9a84c) — inspirada en manuscritos antiguos
- **Temas mensuales**: Claridad, Pasiones, Conciencia, Pensamiento imparcial, Acción correcta, Resolución de problemas, Deber, Pragmatismo, Fortaleza, Virtud, Amor fati, Mortalidad

---

*«La filosofía es la medicina del alma» — Marco Aurelio*
