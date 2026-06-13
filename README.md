# Домашнее задание
# Git: ветки, слияние и Pull Request

## Описание проекта
Тренировка создания веток, локальное слияние и PR
Код выводит на печать информацию обо мне, изученные дисциплины и отчет.


## Использованные ветки
| Ветка | Что делал | Как попала в main |
|---|---|---|
| feature/profile | модуль профиля | merge локально |
| feature/subjects | список дисциплин | merge локально |
| feature/report | итоговый отчёт | Pull Request |
| experiment/broken-idea | тестовая идея | удалена без merge |

## Pull request
Сcылка на PR [https://github.com/SpideErik/git_branching_homework/pull/1](https://github.com/SpideErik/git_branching_homework/pull/1)

# Этапы

## Этап 1.
Создание и публикация main

## Этап 2. Ветка feature/profile: первая функция
7. Создал и перешел на ветку feature/profile
![Скриншот](docs/screenshots/07_create_branch.jpg)
12. Скриншот Gitlens после переключения на main
![Скриншот](docs/screenshots/11_branch_graph.jpg)

## Этап 3. Ветка feature/subjects: независимая разработка
20. Скриншот GitLens (до слияния)
![Скриншот](docs/screenshots/20_branch_graph.jpg)

## Этап 4. Ветка feature/report: Pull Request на GitHub
29. Ссылка на pull request https://github.com/SpideErik/git_branching_homework/pull/1
32. Скриншот graph после синхронизации изменений с github
![Скриншот](docs/screenshots/32_after_pull.jpg)

## Этап 5. Ветка experiment/broken-idea: удаление ненужной ветки
36. Проверка, что изменения и файлы исчезают и переключение веток
![Скриншот](docs/screenshots/36_switch_to_main.jpg)
37. Для удаления ветки если она не была слита надо использовать force иначе будет ошибка удаления
![Скриншот](docs/screenshots/37_del_branch.jpg)

# Вывод
Ветки необходимы и для совместной работы и для тестирования новых возможностей и для исправления ошибок.
Благодаря веткам в main можно всегда держать работоспособную версию.
PR позволяет другим участникам просмотреть код перед слиянием и сделать слияние в ветку main безлпаснее.
