# ERP Emprendedor — CITE Madera y del Mueble

Sistema ERP 100% gratuito desarrollado por el **CITE Madera y del Mueble** (ITP — Instituto Tecnológico de la Producción) para MYPE del sector madera y mueblería del Perú.

## Estructura del Proyecto

```
├── erp-sistema/          # Aplicación ERP (SPA)
│   ├── index.html        # Shell principal: login + app
│   └── js/
│       ├── data.js       # Datos mock (materiales, proveedores, clientes, etc.)
│       ├── ui.js         # Componentes UI reutilizables
│       ├── app.js        # Core: init, navegación, dark mode, toasts, modales
│       └── modules/      # 9 módulos funcionales
│           ├── dashboard.js
│           ├── inventario.js
│           ├── compras.js
│           ├── ventas.js
│           ├── produccion.js
│           ├── costos.js
│           ├── finanzas.js
│           ├── rrhh.js
│           └── admin.js
│
└── web-promocional/      # Landing page promocional
    ├── index6.html       # Versión actual
    └── img/              # Imágenes y logos SVG
```

## Stack Tecnológico

| Tecnología | Uso |
|---|---|
| HTML / CSS / JavaScript | Base completa — sin frameworks ni bundlers |
| TailwindCSS v3 (CDN) | Utilidades CSS en el ERP |
| Chart.js (CDN) | Gráficos en el dashboard del ERP |
| GSAP 3.12.5 (CDN) | Animaciones en la web promocional |
| Google Fonts | Inter (body) + Cormorant Garamond (display) |

> **Sin instalación requerida.** No hay `npm`, `node_modules` ni proceso de build. Solo archivos estáticos.

## ERP — 9 Módulos

| # | Módulo | Descripción |
|---|---|---|
| 1 | **Dashboard** | KPIs en tiempo real, alertas y visión general del negocio |
| 2 | **Inventario** | Stock, Kardex, alertas de reposición, valorización |
| 3 | **Compras** | Proveedores, órdenes de compra, flujo de aprobación |
| 4 | **Ventas** | Cotizaciones → OV → Facturas con IGV 18% automático |
| 5 | **Producción** | Kanban, Gantt, BOM, control de mermas |
| 6 | **Costos** | Costo estándar vs real, semáforos de margen |
| 7 | **Finanzas** | Flujo de caja, CxC, CxP, alertas de vencimiento |
| 8 | **RRHH** | Empleados, asistencia, planilla, boletas digitales |
| 9 | **Administración** | Usuarios, roles, permisos, auditoría |

## Acceso al ERP

- **Email:** `admin@citemadera.pe`
- **Contraseña:** `admin123`

Abrir `erp-sistema/index.html` en cualquier navegador.

## Web Promocional

Landing page con animaciones GSAP (ScrollTrigger, parallax, stagger reveals) que presenta el ERP como producto gratuito.

**Secciones:** Hero → Ticker → Módulos → Funciones Clave → Comparativa → FAQ → Gratis → Footer

**Paleta de colores:**

| Token | Color | Uso |
|---|---|---|
| `--bg` | `#FAF8F5` | Fondo principal (crema) |
| `--bg2` | `#EDE6D9` | Fondo alterno |
| `--dark` | `#0D1B2A` | Textos oscuros |
| `--gold` | `#C4902E` | Acento dorado |
| `--green` | `#2A7250` | Éxito / positivo |
| `--muted` | `#6B7A8D` | Texto secundario |

## Cómo Usar

1. Clonar o descargar el repositorio
2. Abrir `erp-sistema/index.html` para el ERP
3. Abrir `web-promocional/index6.html` para la landing page
4. No requiere servidor — funciona directo desde el sistema de archivos

## Institución

**CITE Madera y del Mueble**
Parque Industrial de Villa El Salvador, Lima
[gob.pe/citemadera](https://www.gob.pe/citemadera)

Desarrollado con el respaldo del **ITP — Instituto Tecnológico de la Producción**.

## Licencia

Producto de uso público desarrollado por una institución del Estado Peruano. 100% gratuito, sin restricciones de uso para MYPE del sector madera y mueblería.
