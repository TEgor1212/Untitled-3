# Отчёт о выполнении практических заданий

Дата выполнения: 2026-11-12
Репозиторий: `/home/prinz/git/Untitled-3`
Каталог с результатами: `practical-work/`
Каталог с логами: `practical-logs/`

## Что выполнено (локально, в доступном окружении)

| Задание | Результат | Лог/артефакты |
|---|---|---|
| Bash CLI (`bashCLI.md`) | Созданы все требуемые структуры каталогов (blog, shop, webapp, framework, project-x) командами `mkdir -p`/`touch`, вывод зафиксирован | `practical-logs/bashCLI.log`, `practical-work/bash-cli/` |
| Bash Scripts (`bashScript.md`) | Написаны и проверены скрипты 1–7; написан и успешно запущен скрипт 10 (GitHub stats, с обработкой ошибок) | `practical-logs/bashScript.log`, `practical-work/bash-scripts/scripts/` |
| Mermaid (`Mermaid.md`) | Выполнены все задания уровней 1–4 и задания 5–6 в одном `README.md` (10 диаграмм Mermaid) | `practical-logs/mermaid.log`, `practical-work/mermaid/README.md` |
| Docker History (`DockerHistory.md`) | Подготовлены `README.md` (история/описание/современность/Docker Hub/Dockerfile/Compose) и `info.md` с заметками | `practical-logs/dockerHistory.log`, `practical-work/docker-history/` |
| Привлекательный README (`beautifulREADME.md`) | Создан пример проекта с навигацией, якорями, списками, цитатами, таблицей задач, кодом Java и Mermaid-диаграммами | `practical-logs/beautifulREADME.log`, `practical-work/beautiful-readme/` |
| Документация качества (`DocsGitMarkdown.md`) | Создана структура `healthmonitor-quality-docs` со всеми требуемыми файлами и заполненным `README.md` (таблица контактов, ссылки) | `practical-logs/docsGitMarkdown.log`, `practical-work/docs-quality/` |
| Портфолио (`CreatingPortf.md`, частично) | Создан локальный шаблон `my-dev-portfolio` с `README.md`, `.gitignore`, примером проекта | `practical-logs/creatingPortfolio.log`, `practical-work/portfolio/` |
| Скрипт синхронизации репозиториев (`scriptSyncRep.md`) | Написаны `sync-repos.sh` и `sync-repos.ps1` с README; bash-скрипт проверен (`bash -n`) | `practical-logs/scriptSyncRep.log`, `practical-work/script-sync/` |
| Скрипт обновления приложений (`upgradeAlApps.md`) | Написаны `upgrade-all.sh` (apt/macOS) и `upgrade-all.ps1` (winget) с README; bash-скрипт проверен | `practical-logs/upgradeAlApps.log`, `practical-work/upgrade-apps/` |
| Docker-образы (`ready_made_docker_image.md`/`DockerImages.md`, частично) | Проверена среда Docker; успешно выполнен `docker run --rm hello-world`. Попытка запуска `alpine` не удалась из-за сетевой ошибки registry в окружении | `practical-logs/dockerImages.log` |

## Что не может быть полностью выполнено автоматически в данном окружении

Некоторые задания требуют действий/артефактов вне возможностей локального CLI-агента или зависят от внешних сервисов и пользовательских аккаунтов:

- **Создание/публикация репозиториев на GitHub/Gitflic, push, Pull Request, GitHub Pages, CI/CD Deployments/Environments, Collaborators** — требуют учётных записей и сетевого доступа/авторизации к этим сервисам из-под пользователя.
- **Скриншоты GUI** (VS Code, браузер, GitHub, статистика слепой печати, WSL в Windows, VirtualBox+Alt Linux, Docker Desktop, результаты в терминале в виде изображений) — нельзя сделать/вложить как реальные скриншоты рабочего стола.
- **Командные проекты** (`TeamDevelopment.md`, `Teams_DeployStaticSite.md`) — требуют формирования команды, распределения ролей и совместной работы нескольких людей.
- **Полные циклы Dockerfile/Docker Compose/готовых образов** (`DockerfileTasks.md`, `DockerImages.md`, `ready_made_docker_image.md`) — частично ограничены сетью (pull образов), GUI-требованиями и объёмом; в окружении нет `jq/tree`, а часть образов недоступна для скачивания.
- **Синхронизация с внешними удалёнными репозиториями** — скрипты подготовлены и проверены синтаксически, но не запускались против реальных приватных/удалённых репозиториев пользователя.

## Итог
Все задания, которые можно реализовать программно в текущем окружении, выполнены: созданы структуры, скрипты, документация и диаграммы, выполнены проверяемые команды, а логи сохранены в отдельные файлы в каталоге `practical-logs/`.
