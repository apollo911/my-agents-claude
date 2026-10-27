# my-agents-claude

Субагенты для Claude Code.

| Агент | Что делает |
|---|---|
| [ai-digest-editor](.claude/agents/ai-digest-editor.md) | Собирает дайджест новостей ИИ и автоматизации и готовит пост для Telegram-канала |

## Установка

Для всех проектов на компьютере скопируйте файлы из `.claude/agents/` в `~/.claude/agents/`.

Windows (cmd):
```cmd
git clone https://github.com/apollo911/my-agents-claude
mkdir "%USERPROFILE%\.claude\agents"
copy "my-agents-claude\.claude\agents\*.md" "%USERPROFILE%\.claude\agents\"
```

Если работать внутри этого репозитория, агенты подхватываются автоматически.
