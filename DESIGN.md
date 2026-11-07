# TasaVzla — Paleta de colores y diseño

## Colores

| Token | Valor | Uso |
|-------|-------|-----|
| `background.primary` | `#0a0a0f` | Fondo principal de pantalla (casi negro azulado) |
| `background.secondary` | `#1a1a2e` | Fondo secundario |
| `background.tertiary` | `#16213e` | Fondo terciario |
| `white-primary` | `#ffffff` | Texto principal y elementos claros |
| `green-primary` | `#00ff88` | Verde neón — acento principal, tasas, éxito |
| `blue-primary` | `#3b82f6` | Azul — acento secundario, moneda extranjera |
| `wine` | `#dc2626` | Rojo / vino — estados de error |
| `wine-dark` | `#b91c1c` | Rojo oscuro — variantes de error |

### Variantes de opacidad usadas
- `text-white-primary/70`, `/60`, `/40` — texto secundario y terciario
- `bg-white/5`, `bg-white/10` — fondos sutiles en inputs y tarjetas
- `bg-green-primary/20`, `bg-blue-primary/20` — fondos de iconos de moneda
- `bg-black/20` — overlay del fondo
- `rgba(255,255,255,0.05)` / `rgba(0,0,0,0.3)` — vidrio esmerilado

## Tipografía

- **Familia:** Inter (Google Fonts`)
- **Pesos:** 400 (Regular), 500 (Medium), 600 (SemiBold), 700 (Bold)
- **Utilidad Tailwind:** `font-sans`

## Estilo visual (Design System)

- **Modo oscuro exclusivo:** fondo principal `#0a0a0f` en toda la app.
- **Glassmorphism:** tarjetas con `backdrop-filter: blur`, borde de 1px `rgba(255,255,255,0.1)` y fondo semitransparente (`glass` y `glass-dark` en `global.css`).
- **Bordes redondeados grandes:** `rounded-3xl`, `rounded-2xl`, `rounded-xl` en tarjetas y botones.
- **Degradados lineales:** combinación verde `#00ff88` → azul `#3b82f6`.
- **Fondo animado:** degradado radial con tres resplandores difusos (verde, azul y rojo) en las esquinas, más un overlay negro semitransparente.
- **Iconografía:** phosphor-icons/react.
- **Animaciones:** `react-native-reanimated` con `fadeInUp`, `fadeInDown`, pulsos (`PulseDot`) y escalas sutiles en botones de selección.
