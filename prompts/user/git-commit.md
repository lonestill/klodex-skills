---
id: git-commit
name: Conventional Git Commit Generator
type: user
slash: /commit
category: code
version: 1.0.0
author: lonestill
description: Пользовательский шаблон: анализ последних изменений (git diff / git status) и формирование чистого Conventional Commit без лишней воды.
tags: ["git", "commit", "workflow", "vcs"]
---

Проанализируй текущий `git diff` и незакоммиченные изменения в репозитории:

1. **Тип коммита:** выбери точный префикс по спецификации Conventional Commits (`feat`, `fix`, `refactor`, `perf`, `test`, `chore`, `docs`).
2. **Краткий заголовок:** лаконичное описание сути изменения до 60 символов в повелительном наклонении (без точки в конце).
3. **Детали (если изменение комплексное):** маркированный список из 2-4 пунктов с описанием неочевидных инженерных решений и мотивации.
4. **Вывод:** выведи готовое сообщение коммита в блоке `git commit -m "..."`.
