# Topics del repositorio

Este archivo contiene los "topics" recomendados para el repositorio y la instrucción para aplicarlos mediante la API de GitHub (requiere un token con permisos `repo`).

Topics recomendados:

- claude-code
- free-claude-code
- 9router
- ai
- llm
- proxy
- api-proxy
- free-models
- open-source
- cli
- dashboard
- routing
- orchestration
- ollama
- vertex-ai
- openrouter
- groq
- deepseek
- kiro-ai

Cómo aplicar los topics vía API (reemplaza <YOUR_GITHUB_TOKEN> por un token con permisos `repo`):

```bash
curl -X PUT \
  -H "Accept: application/vnd.github+json" \
  -H "Authorization: Bearer <YOUR_GITHUB_TOKEN>" \
  https://api.github.com/repos/nocloudware/Free-Claude-Code-9router/topics \
  -d '{"names": ["claude-code","free-claude-code","9router","ai","llm","proxy","api-proxy","free-models","open-source","cli","dashboard","routing","orchestration","ollama","vertex-ai","openrouter","groq","deepseek","kiro-ai"]}'
```

Notas:
- Este archivo lo he creado directamente en la rama por defecto del repositorio.
- Si quieres, puedo intentar aplicar los topics automáticamente mediante la API; necesitaré que pegues un token con permisos `repo` (puedes revocarlo después).