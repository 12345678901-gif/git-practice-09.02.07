# Contributing

## Правила оформления коммитов (Conventional Commits)

Формат: `<type>(<scope>): <description>`

Типы:
- `feat` — новая функциональность
- `fix` — исправление бага
- `docs` — документация
- `style` — форматирование (без изменения логики)
- `refactor` — рефакторинг
- `test` — тесты
- `chore` — служебные задачи (CI, зависимости)
- `ci` — изменения CI

Примеры:
- `feat(calculator): add division function`
- `fix: handle division by zero`
- `docs: update README`

## Процесс
1. Создайте Issue.
2. Создайте ветку `feature/<name>-#<issue>`.
3. Сделайте PR в main с `Closes #<issue>`.
4. Дождитесь approve и успешного CI.
5. Выполните merge.
