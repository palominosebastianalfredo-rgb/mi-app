# Instalar las mismas herramientas en tu ordenador

Requisitos: [Node.js LTS](https://nodejs.org), [Git](https://git-scm.com) y Claude Code:

```bash
npm install -g @anthropic-ai/claude-code
```

Las skills ya vienen dentro de esta carpeta (`.claude/skills/`): si abres Claude Code
dentro de `mi-app`, funcionan sin instalar nada más.

## Plugins recomendados (opcionales, se instalan una vez para todos tus proyectos)
Escríbelos dentro de Claude Code:

```
/plugin install superpowers@claude-plugins-official
/plugin install frontend-design@claude-plugins-official
/plugin install playwright@claude-plugins-official
/plugin install context7@claude-plugins-official
```

Según tu app:

```
/plugin install supabase@claude-plugins-official     # base de datos + login
/plugin install vercel@claude-plugins-official       # publicar la web
/plugin install expo@claude-plugins-official         # app móvil iPhone/Android
/plugin install figma@claude-plugins-official        # si diseñas en Figma
/plugin install stripe@claude-plugins-official       # cobrar pagos
```

> Si instalas el plugin `superpowers` o `frontend-design`, puedes borrar las copias
> equivalentes de `.claude/skills/` para no tenerlas duplicadas.
