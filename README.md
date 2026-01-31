# MiColeEnLinea - Prototipos Web

> **IMPORTANTE: Este repo es SOLO para prototipos visuales.**
> **NO contiene codigo de produccion.**
> **NO debe mergearse a ningun otro repositorio.**

## Que es esto?

Prototipos HTML estaticos para el rebranding del frontend web de MiColeEnLinea.
Usan Tailwind CSS via CDN y Plus Jakarta Sans.

## Como ver los prototipos

```bash
# Abrir el navegador de prototipos
open index.html
```

O simplemente abre `index.html` en tu navegador.

## Estructura

```
prototypes/web/
├── index.html                # Navegador tipo Storybook
├── template.html             # Base con tokens de diseno
├── components/
│   ├── buttons.html         # Botones (primary, secondary, ghost, loading)
│   ├── inputs.html          # Inputs, selects, checkboxes, validacion
│   ├── cards.html           # NotificationCard, StatCard, StudentCard
│   └── badges.html          # Badges por tipo (Personal, Curso, Escuela)
├── data-display/
│   ├── table-stacked.html   # Tabla responsive (cards en mobile)
│   └── card-list.html       # Lista de cards (mobile-first)
└── screens/
    ├── login.html           # Pantalla de login con gradient
    ├── dashboard-admin.html # Dashboard completo para admin
    ├── dashboard-staff.html # Dashboard simplificado para staff
    ├── students.html        # Cursos y Alumnos con tabs
    ├── notifications.html   # Centro de notificaciones
    ├── notification-create.html # Crear mensaje con plantillas
    └── templates.html       # Gestion de plantillas
```

## Proposito

1. Explorar el nuevo diseno antes de implementarlo en React
2. Probar responsive sin tocar codigo de produccion
3. Validar UX con stakeholders
4. Documentar decisiones de diseno

## Repos de produccion (NO TOCAR desde aca)

- `micoleenlinea-web` - Frontend React/Vite
- `micoleenlinea-mobile` - App React Native/Expo
- `micoleenlinea-api` - Backend Laravel

---

**Este repo es 100% seguro. Solo contiene HTML estatico.**
