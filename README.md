# JESS Vitrofusión

Sitio web para JESS Vitrofusión - Vidrio que cobra vida.

## Descripción

Este es el sitio web oficial de JESS Vitrofusión, donde se muestran las piezas únicas de vitrofusión creadas por Jessica & Carlos desde 1996. El sitio incluye:

- Catálogo de productos (joyas, lámparas, móviles y series limitadas)
- Historia de la marca
- Información de contacto

## Despliegue

Este sitio se despliega automáticamente en GitHub Pages mediante GitHub Actions cada vez que se hace un push a la rama `master`.

## Configuración de GitHub Pages

Para configurar GitHub Pages, sigue estos pasos:

1. Ve a la pestaña "Settings" del repositorio
2. En el menú lateral, haz clic en "Pages"
3. En "Source", selecciona "GitHub Actions"
4. El sitio se desplegará automáticamente con cada cambio en la rama `master`

## Estructura del proyecto

```
.
├── home.html          # Página principal del sitio
├── images/            # Directorio para las imágenes del sitio
├── .github/workflows/ # Workflows de GitHub Actions
│   └── deploy.yml     # Configuración de despliegue automático
└── README.md          # Este archivo
```

## Acceso al sitio

Una vez configurado, el sitio estará disponible en: https://dongeeo87.github.io/Web-Jess/