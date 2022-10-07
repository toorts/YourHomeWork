![Git](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e0/Git-logo.svg/2560px-Git-logo.svg.png)

# Инструкция по работе с Git

# 1 часть

## Версия
```bash
git version
```
## Инициализация
```bash
git init
```
## Статус
```bash
git status
```
## Добавить файл(ы) в проект
```bash
git add <имя_файла>
git add .
```
## Фиксация
```bash
git commit -m "комментарий"
```
## Просмотр истории коммитов
```bash
git log
```
## Переместить указатель HEAD
```bash
git checkout <sha>
git checkout <branch>
```
## Выгрузка в удаленный репозиторий
```bash
git push
```

![](https://miro.medium.com/max/990/1*_UUaozFPd2qHfCFjlhIgGA.png "При пожаре")

# 2 часть

## Создание веток

```bash
git branch - отображение всех веток
git branch <название ветки> - добавление новой ветки
```
## Слияние веток
```bash
git merge <название ветки>
```
>Перед слиянием веток необходимо убедиться, что базовая и принимаемая ветки указаны верно

## Сравнение
```bash
git diff
```

## Сохранение неподтвержденных изменений
```bash
git stash
```

## Создание тега
```bash
git tag <tagname>
```

## Отображение метаданных автора
```bash
git blame <file_name>
```

## Клонирование
```bash
git clone <repo url>
```

## Удаление ветки
```bash
git branch -d <branch_name>
```
>-d – флаг, опция команды git branch, сокращенный вариант записи --delete. Как и следует из названия, предназначен для удаления ветки