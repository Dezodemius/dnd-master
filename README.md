# Мастер D&D — кузница приключений

Помогает мастеру (DM) Dungeons & Dragons 5e готовить материал к игре: цельные приключения и ваншоты, NPC и фракции, сбалансированные энкаунтеры и боёвку, локации, подземелья и лор. Поддерживает редакции 2014 и 2024 (по умолчанию 2014). Используй этот скилл, когда пользователь просит «создай приключение», «накидай ваншот / one-shot», «придумай сюжет для сессии», «нужен NPC / непись», «собери фракцию», «собери / сбалансируй энкаунтер», «накидай боёвку», «придумай подземелье / локацию / город / таверну», «придумай лор / зацепку / квест», а также на любые запросы вида «я мастер днд, помоги с…», «подготовь сессию D&D / DnD», «придумай злодея / монстра / ловушку / сокровище». Весь генерируемый материал — на русском, готовый к использованию за столом.

Скилл в формате [Agent Skills](https://agentskills.io): работает в Claude, Codex, Gemini CLI и других ИИ-агентах, а однофайловая версия — в любом чате.

## Примеры запросов

> Накидай ваншот на 4 часа для 4 игроков 3 уровня, тон — тёмное фэнтези.

> Собери тяжёлый энкаунтер для партии из 5 персонажей 6 уровня в болотах (редакция 2024).

> Нужен NPC: трактирщик, который тайно сдаёт постояльцев культу.

## Установка

Готовые файлы лежат в [релизах](https://github.com/Dezodemius/dnd-master/releases/latest).

| Где пользуетесь | Как подключить |
| --- | --- |
| **claude.ai**, Claude Desktop | Скачать [`dnd-master.zip`](https://github.com/Dezodemius/dnd-master/releases/latest/download/dnd-master.zip) → Настройки → Возможности → Skills → загрузить. В Desktop можно открыть [`dnd-master.skill`](https://github.com/Dezodemius/dnd-master/releases/latest/download/dnd-master.skill) двойным кликом |
| **Claude Code** | `/plugin marketplace add Dezodemius/agent-skills`, затем `/plugin install dnd-master@dezodemius-skills` |
| **Codex, Gemini CLI, Cursor, GitHub Copilot, OpenCode** и другие агенты | `npx skills add Dezodemius/dnd-master` |
| **ChatGPT, Gemini, DeepSeek, Qwen, Grok, Алиса, GigaChat** и другие чаты | Скачать [`dnd-master.prompt.md`](https://github.com/Dezodemius/dnd-master/releases/latest/download/dnd-master.prompt.md) и приложить в начале чата или вставить в инструкции проекта / GPT / Gem |

Подробно по каждой платформе — в [каталоге](https://github.com/Dezodemius/agent-skills#установка).

## Связка D&D-скиллов

Скиллы работают и по отдельности, и цепочкой: сюжет → механика → книга.

| Скилл | Роль |
| --- | --- |
| [folklore-myth](https://github.com/Dezodemius/folklore-myth) | сюжетная основа из мифов и фольклора |
| [writers-council](https://github.com/Dezodemius/writers-council) | консилиум писателей разворачивает тему в сюжет |
| [pantheons](https://github.com/Dezodemius/pantheons) | боги, культы, домены жрецов |
| [dnd-master](https://github.com/Dezodemius/dnd-master) | правила 5e, баланс, NPC, локации |
| [dnd-module](https://github.com/Dezodemius/dnd-module) | вёрстка в книгу-модуль, наполнение карты |

Полный каталог: [Dezodemius/agent-skills](https://github.com/Dezodemius/agent-skills).

## Выпуск релиза

Релиз собирается автоматически по тегу из четырёх чисел на коммите из `main`:

```bash
git tag 1.0.0.0 && git push origin 1.0.0.0
```

Общий CD и проверки живут в [Dezodemius/agent-skills](https://github.com/Dezodemius/agent-skills).

## Лицензия

Apache License 2.0 — см. [LICENSE](LICENSE) и [NOTICE](NOTICE).
