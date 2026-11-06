# Mi App — instrucciones para Claude

Responde siempre en español.

## Flujo de trabajo obligatorio (de idea a app)
1. **Idea → especificación**: usa la skill `brainstorming`. Haz preguntas de una en una, propone 2–3 enfoques y no escribas código hasta que el usuario apruebe el diseño. Guarda la especificación en `docs/especificacion.md`.
2. **Dirección visual**: antes de cualquier pantalla, usa `ui-ux-pro-max` para generar el sistema de diseño (paleta, tipografías, estilo) y `frontend-design` para elegir una dirección estética con personalidad. Guárdalo en `DESIGN.md`.
3. **Plan**: usa `writing-plans` para dividir el trabajo en tareas pequeñas en `docs/plan.md`.
4. **Construcción**: usa `executing-plans` / `subagent-driven-development` y `test-driven-development`. Para React/Next.js sigue `react-best-practices` y `composition-patterns`; para móvil (Expo) sigue `react-native-skills`.
5. **Pulido y revisión**: usa `impeccable` (critique / audit / polish) y `web-design-guidelines` para accesibilidad y UX. Verifica en navegador real con `webapp-testing`.
6. **Antes de decir "listo"**: `verification-before-completion` (ejecutar, probar, captura de pantalla).
7. **Publicar**: `deploy-to-vercel` (web) o EAS de Expo (móvil).

## Stack por defecto (salvo que el usuario elija otro)
- Web: Next.js (App Router) + TypeScript + Tailwind CSS + shadcn/ui
- Móvil: Expo (React Native) + Expo Router
- Backend / login / base de datos: Supabase
- Hosting: Vercel

## Reglas
- Commits pequeños y frecuentes, con mensajes en español.
- Nada de secretos (API keys) en el código: usar `.env.local` (ya está en `.gitignore`).
- Explica cada paso en lenguaje sencillo: el usuario está aprendiendo.
