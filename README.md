# TasaVzla

Landing page del proyecto TasaVzla: una app móvil para consultar la tasa oficial del BCV, convertir montos en bolívares, dólares y euros, y compartir resultados rápidamente.

## Descripción

Este repositorio contiene el sitio web promocional y de presentación de TasaVzla, construido con Astro y Tailwind CSS. Su objetivo es presentar la app a usuarios de Samsung Galaxy Store y explicar su propuesta de valor antes de instalarla.

La página incluye:

- Hero con la propuesta principal: tasa oficial del BCV siempre a un toque
- Vista de pantallas de la app
- Sección de funcionalidades
- Explicación del flujo de uso
- Enlace a la política de privacidad

## Stack

- Astro
- React
- Tailwind CSS
- Phosphor Icons

## Requisitos

- Node.js >= 22.23.4
- pnpm

## Instalación

```bash
pnpm install
```

## Scripts

```bash
pnpm dev
pnpm build
pnpm preview
pnpm astro -- --help
```

### Comandos disponibles

| Comando | Acción |
| :--- | :--- |
| `pnpm install` | Instala las dependencias del proyecto |
| `pnpm dev` | Inicia el servidor de desarrollo en `localhost:4321` |
| `pnpm build` | Genera la versión de producción en `./dist/` |
| `pnpm preview` | Previsualiza el sitio construido localmente |
| `pnpm astro ...` | Ejecuta comandos del CLI de Astro |

## Estructura del proyecto

```text
/
├── public/
│   ├── favicon.ico
│   └── favicon.svg
├── src/
│   ├── assets/
│   │   ├── Screenshot_TasaVzla-1.webp
│   │   └── Screenshot_TasaVzla-2.webp
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   │   ├── index.astro
│   │   └── privacidad.astro
│   └── styles/
│       └── global.css
├── package.json
├── pnpm-lock.yaml
├── astro.config.mjs
├── README.md
└── tsconfig.json
```

## Sitio y distribución

- Página principal: `/`
- Política de privacidad: `/privacidad`
- Descarga de la app: Galaxy Store (enlace indicado en la landing)
