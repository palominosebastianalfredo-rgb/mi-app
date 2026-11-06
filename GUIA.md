# Guía: de una idea a una app publicada

## Los pasos
| # | Paso | Qué haces tú | Skill que ayuda |
|---|------|--------------|-----------------|
| 1 | **Idea** | Rellenas `PROMPT-INICIAL.md` y se lo pegas a Claude | `brainstorming` |
| 2 | **Especificación** | Respondes preguntas y apruebas el diseño | `brainstorming` → `docs/especificacion.md` |
| 3 | **Diseño visual** | Eliges estilo, colores, tipografías | `ui-ux-pro-max`, `frontend-design`, `theme-factory` |
| 4 | **Plan** | Revisas la lista de tareas | `writing-plans` |
| 5 | **Construir el MVP** | Pruebas cada pantalla y das feedback | `executing-plans`, `test-driven-development`, `react-best-practices` / `react-native-skills` |
| 6 | **Pulir la interfaz** | Pides "critica y pule esta pantalla" | `impeccable`, `web-design-guidelines` |
| 7 | **Probar** | Claude abre un navegador real y saca capturas | `webapp-testing`, `verification-before-completion` |
| 8 | **Arreglar errores** | Describes qué falla | `systematic-debugging` |
| 9 | **Publicar** | Creas cuenta en Vercel (web) o Expo (móvil) | `deploy-to-vercel` |
| 10 | **Mejorar** | Usuarios reales → nuevas funciones (vuelves al paso 1) | todo el ciclo |

## Web o móvil
- **Empieza por web** si es tu primera app: se ve en cualquier móvil desde el navegador, se publica gratis en minutos y no necesitas cuentas de Apple/Google.
- **Móvil nativa (Expo)** si necesitas cámara, notificaciones push, GPS en segundo plano o estar en las tiendas. Publicar en App Store cuesta 99 USD/año y en Google Play 25 USD una vez.

## Skills instaladas (en `.claude/skills/`)
**Flujo de trabajo — obra/superpowers** (el repositorio de skills más popular de GitHub):
`brainstorming`, `writing-plans`, `executing-plans`, `subagent-driven-development`, `test-driven-development`, `systematic-debugging`, `verification-before-completion`, `requesting-code-review`, `receiving-code-review`, `using-superpowers`.

**Diseño e interfaz:**
- `frontend-design` (Anthropic, oficial) — la skill de diseño más instalada; evita el aspecto "genérico de IA".
- `ui-ux-pro-max` (nextlevelbuilder) — base de datos de estilos, paletas, tipografías y guías UX para web y móvil.
- `impeccable` (Paul Bakaus) — critica, audita, pule y anima interfaces existentes.
- `theme-factory` (Anthropic) — temas de color y fuentes listos para usar.
- `web-design-guidelines` (Vercel) — revisión de accesibilidad y buenas prácticas.

**Código y publicación — Vercel:** `react-best-practices`, `composition-patterns`, `react-native-skills`, `deploy-to-vercel`.

**Pruebas — Anthropic:** `webapp-testing` (Playwright: navegador real, capturas, consola).

## Lo que dejé fuera a propósito
- **taste-skill** (Leonxlnx): muy buena para webs de empresa/landing pages, pero pesa 40 MB y se solapa con las otras tres de diseño. Instálala si tu "app" es sobre todo una web de presentación.
- Demasiadas skills de diseño a la vez compiten entre sí; con 3 bien elegidas basta.

## Cuentas que necesitarás (gratis para empezar)
GitHub (guardar código) · Vercel (publicar web) · Supabase (base de datos y login) · Expo (solo si es móvil).
