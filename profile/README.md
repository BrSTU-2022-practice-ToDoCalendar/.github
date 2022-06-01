## Hi there 👋

Эта организация для технологической практики.

Разработка будет вестись в двух репозиториях:
- [ToDoCalendar_backend](https://github.com/ToDoCalendar/ToDoCalendar_backend) - Python
- [ToDoCalendar_frontend](https://github.com/ToDoCalendar/ToDoCalendar_frontend) - JS

## Git Workflow

Пример git веток для репозитория фронтендеров:

```
.       
`-- main (master)
    `-- dev
        |-- galanin
        |-- prokopchik
        `-- yuryev                                                             
```

### Cвоя ветка => dev

1. Каждый будет вести разработку в своёй ветке. Например, под своей фамилией.
2. Как закончили делать фичу - делаем pull request в ветку `dev`.
3. Когда делаем pull request вы не сможете сделать merge, так как кто-то должен проверить ваш код. Добавьте кого-то в reviewer'ы.
4. Как reviewer сделает approve, то у вас будет возможность сделать merge.
5. Сделали merge - теперь ваш код в ветке `dev`.

### dev => main

Если все замечательно работает в ветке dev, то пора добавлять всё в основную ветку `main` (master).

Алгоритм тот же:
1. Делаем пул реквест.
2. Добавляет ревьювера.
3. Ревьювер проверяет код.
4. Ревьювер дает апрув.
5. Делаем мердж в ветку `main`.
