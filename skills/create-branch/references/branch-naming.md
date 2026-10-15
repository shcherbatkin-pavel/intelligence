# Соглашение об именовании веток

Это выбранное соглашение для скила, а не требование Git или Conventional Commits.

Используй формат `<тип>/<описание>`. Пиши описание на английском языке строчными буквами, разделяя слова дефисами.

| Тип | Назначение | Пример |
| --- | --- | --- |
| `feat` | Новая возможность | `feat/create-commit-skill` |
| `fix` | Исправление ошибки | `fix/invalid-config` |
| `hotfix` | Срочное исправление в production | `hotfix/login-crash` |
| `docs` | Документация | `docs/installation-guide` |
| `refactor` | Рефакторинг | `refactor/config-loader` |
| `chore` | Обслуживание проекта | `chore/update-dependencies` |
| `release` | Подготовка релиза | `release/prepare-next-version` |

Если пользователь указал идентификатор задачи, используй формат `<тип>/<идентификатор>-<описание>`, сохраняя регистр идентификатора. Например: `feat/PROJ-123-create-commit-skill`.

Для релиза с указанной версией используй `release/<версия>`, например `release/1.2.0`.

Имя также должно соответствовать [техническим ограничениям Git](https://git-scm.com/docs/git-check-ref-format). Проверяй его через `git check-ref-format --branch` перед созданием ветки.
