## Группа команд git remote

Группа команд ***git remote*** состоит из следующих команд:

1. ***git remote add** [имя репозитория] [адрес удаленного репозитория]* - устанавливает связь между текущим (локальным) и указанным в команде удаленным репозиторием.

***Примечание!** При использовании команды git remote add оба репозитория долждны существовать.*

2. **git remote** - отображает список связей текущего (локального) репозитория с удаленными.

3. ***git remote remove** [имя репозитория]* - удаляет связь между текущим (локальным) репозиторием и указанным в команде (удаленным).

Пример выполнения комнады ***git remote add***:

```bash=
git remote add [my_rest_repo] [https://github.com/mobacsell/test]
```

[***Вернуться к оглавлению***](../readme.md)