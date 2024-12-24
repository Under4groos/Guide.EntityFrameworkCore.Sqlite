# Microsoft.EntityFrameworkCore.Sqlite Guide

1. Download SqliteBrowser
```
https://sqlitebrowser.org/
```
2. Создаем БД

![](https://raw.githubusercontent.com/Under4groos/Guide.EntityFrameworkCore.Sqlite/refs/heads/master/img/DB_Browser_for_SQLite_knrNXScCBb.png)

3. Создаем в БД нашу таблицу. 
Пример: 
![](https://raw.githubusercontent.com/Under4groos/Guide.EntityFrameworkCore.Sqlite/refs/heads/master/img/DB_Browser_for_SQLite_SfzIqHRbMV.png)


4. Открываем Visual Studio -> Консоль диспетчера пакетов.

![](https://raw.githubusercontent.com/Under4groos/Guide.EntityFrameworkCore.Sqlite/refs/heads/master/img/devenv_ZUnbcSoI5k.png)

5. Вводим следующее:
<path_sqlite> - путь к базе дыннх.
```C++
Scaffold-DbContext "DataSource=<path_sqlite>" Microsoft.EntityFrameworkCore.Sqlite
```

### После всех манипуляций у нас в проектк появятся классы. 

![](https://raw.githubusercontent.com/Under4groos/Guide.EntityFrameworkCore.Sqlite/refs/heads/master/img/devenv_0wfkw5TWc9.png.png)
