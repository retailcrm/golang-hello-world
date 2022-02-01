# golang-hello-world
Тестовое задание на позицию Go разработчика

# Описание задания

Написать консольную утилиту для получения списка репозиториев GitHub аккаунта, указанного в аргументе, а также список релизов для каждого репозитория в этом аккаунте.
Полученную информацию вывести в консоль в виде отсортированного списка релизов для каждого репозитория. 
В случае ошибки при получении данных по API необходимо корректно завершить работу программы и вывести ошибку. 
Покрыть функционал тестами.

# Пример работы утилиты

#### Успешный запуск

```
$ ./github-scanner symfony
symfony/symfony
6.0.0
5.4.0
5.3.1
...

symfony/validator
5.3.1
...
```
#### Запуск с ошибкой
```
$ ./github-scanner qweqwe123123
Account `qweqwe123123` not found.
```

# Требования к реализации
1. При реализации можно использовать пакеты [стандартной Go-библиотеки](https://pkg.go.dev/std). Внешние библиотеки для реализации не требуются
2. Результат оформите в виде GitHub-репозитория и пришлите нам ссылкой

# Полезные материалы
- [Общее описание REST API GitHub](https://docs.github.com/en/rest) 
- [Метод для получения списка репозиториев](https://docs.github.com/en/rest/reference/repos)
- [Метод для получения списка релизов](https://docs.github.com/en/rest/reference/releases) 

# Что для нас важно
Мы смотрим на полноту реализации, качество реализации с точки зрения дальнейшей поддержки утилиты и продуманность с точки зрения граничных кейсов.

Удачи в реализации 👋
