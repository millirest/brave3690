# Подсказка по GIT

### Создание репозитория

```sh
git init
```

### Добавление файл к отслеживанию/индексирование
```sh
git add
```
### Фиксирование файл с комментарием
```sh
git commit -m "<Massage_text>"
```

### Просмотреть подробно историю коммитов/сохранений
```sh
git log
```

### Просмотреть истрию коммитов менее подробно
```sh
git log --oneline
```

### Отображение графа
```sh
git log --graph
```
*Так же можно совмещать c предыдущим примером*

```sh
git log --oneline --graph
```

### Перейти к определённому состоянию файлов
```sh
git checkout <commite>
```

### Перейти к ветке "master"

*"Master" - Основная ветвь*

```sh
git checkout <master>
```

## Работа с ветками

### Отображение всех веток

```sh
git branch
```

Это картинка:
![Пример](Resources/Images/Branch.JPG)

*Звездочкой помечано текущая ветка*

### Создание ветки

```sh
git branch <Имя_новой_ветки>
```

### Переход к ветке
```sh
git checkout <Название_ветки>
```

### Слияние веток

Команда выполняет слияние ветки с текущей веткой. 

```sh
git merge <Название_ветки>
```

### Удаление ветки

```sh
git branch -d <имя_ветки>
```