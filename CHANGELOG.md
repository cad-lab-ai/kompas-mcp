# История версий

## 0.8.0 — 2026-10-28

Первый публичный релиз. Главное в нём:

- Установщик сам прописывает MCP-сервер в Claude Code, Claude Desktop, Cursor, VS Code (Copilot), Codex,
  Gemini CLI, Windsurf и LM Studio и кладёт навык `kompas-engineering` в их папки навыков.
- Инструмент `feedback`: отзыв разработчикам с согласия человека в чате; выключается `install.ps1 -Feedback off`.
- Свой КОМПАС агента: `instance_start` запускает отдельное окно КОМПАС, чтобы агент не мешал вашей работе.
