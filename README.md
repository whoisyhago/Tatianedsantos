# Tatiane Dos Santos · Atelier Florescer

Página web oficial de la artista plástica Tatiane Dos Santos ([@tatiane_d.santos](https://www.instagram.com/tatiane_d.santos/) · [@florescertds](https://www.instagram.com/florescertds/)).

Sitio estático de una sola página (HTML + CSS + JS, sin dependencias). Estilo boutique de lujo.

## Estructura

```
tatiane-web/
├── index.html      # Toda la página (HTML, CSS y JS en un solo archivo)
├── img/            # Fotos de la artista y sus obras
│   ├── tatiane-1.jpg   (exposición, vestido iridiscente, obras circulares)
│   ├── tatiane-2.jpg   (retrato "Cacique", vestido amarillo)
│   └── tatiane-3.jpg   (obra circular violeta, galería blanca)
└── README.md
```

**Importante:** guarda las tres fotos en la carpeta `img/` con esos nombres exactos. Si falta alguna imagen, la página muestra degradados elegantes como reserva y sigue funcionando.

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo `tatiane-web`).
2. Sube todos los archivos de esta carpeta (arrastrándolos en "uploading an existing file" o con git):
   ```bash
   git init
   git add .
   git commit -m "Web de Tatiane Dos Santos"
   git branch -M main
   git remote add origin https://github.com/TU_USUARIO/tatiane-web.git
   git push -u origin main
   ```
3. En el repositorio: **Settings → Pages → Source: Deploy from a branch → Branch: main / (root) → Save**.
4. En 1–2 minutos la web estará en `https://TU_USUARIO.github.io/tatiane-web/`.

## Personalizar

- **Email de contacto:** busca `hola@tatianedossantos.art` en `index.html` y cámbialo.
- **Obras y precios:** edita las tarjetas de la sección "Obras de la Temporada".
- **Colores:** variables al inicio del CSS (`--ink`, `--gold`, etc.).
