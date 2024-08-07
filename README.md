# Планировщик задач (To Do list)

### Описание функционала 
Планировщик задач хранит задачи, каждая из них содержит дату дедлайна и заголовок с комментарием. 

Задачи могут повторяться по заданным правилам: ежегодно и через задаваемое пользователем количество дней. 
Если отметить такую задачу как выполненную, она переносится на следующую дату в соответствии с правилом.

Обычные задачи при выполнении будут просто удаляться.

### Реализовано API со следующими CRUD-операциями:
- добавить задачу;
- получить список задач;
- удалить задачу;
- получить параметры задачи;
- изменить параметры задачи;
- отметить задачу как выполненную.


### Инструкция по локальному запуску
Программа запускается через терминал командой:

```go run .```

Далее в браузере по адресу ```http://localhost:7540/``` запускается сам планировщик задач.

Тесты запускаются через второй терминал (при запущенной программе в первом терминале) командой: 

```go test ./tests```
