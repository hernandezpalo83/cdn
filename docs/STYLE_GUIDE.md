# 🎨 Brand Style Guide - hernandezpalo.es

## 1. Visión General
Esta guía define los estándares visuales para la marca personal de **hernandezpalo**. El objetivo es proyectar una imagen que equilibre la **solidez técnica** con la **visión estratégica de producto**.

---

## 2. Paleta de Colores
Utilizamos una paleta basada en el "Tech Professionalism", con contrastes altos para garantizar la accesibilidad.

| Color | HEX | Uso |
| :--- | :--- | :--- |
| **Primary (Brand)** | `#007AFF` | Botones principales, enlaces, bordes activos. |
| **Dark (Background)** | `#0F172A` | Fondo principal (Modo oscuro / Slate 900). |
| **Surface (Card)** | `#1E293B` | Tarjetas de proyectos, secciones secundarias. |
| **Text Primary** | `#F8FAFC` | Títulos y cuerpo de texto principal. |
| **Text Secondary** | `#94A3B8` | Descripciones, fechas y metadatos. |
| **Accent (Success)** | `#10B981` | Badges de "Disponible", estados completados. |

---

## 3. Tipografía
La tipografía debe ser moderna, geométrica y legible.

- **Fuente Principal:** Inter / Montserrat (Sans-serif).
- **Fuente Mono:** JetBrains Mono (Para bloques de código y métricas).

### Jerarquía:
- **H1 (Hero):** 2.5rem / 40px (Bold 700)
- **H2 (Secciones):** 1.875rem / 30px (SemiBold 600)
- **Body:** 1rem / 16px (Regular 400)

---

## 4. Componentes de UI (Design Tokens)

- **Radio de borde (Border Radius):** `8px` (Rounded-lg).
- **Tarjetas:** Fondo `#1E293B` con borde sutil de `1px solid #334155`.
- **Botones:** `12px 24px` de padding con efecto hover de elevación.

---

## 5. Aplicación en CSS (Variables)
```css
:root {
  --color-primary: #007aff;
  --color-bg: #0f172a;
  --color-surface: #1e293b;
  --color-text-main: #f8fafc;
  --color-text-muted: #94a3b8;
  --radius-main: 8px;
}
