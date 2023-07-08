### Задание 3.

Подключить дополнительный репозиторий MySQL. Установить любой пакет
из этого репозитория.

### Реализация

Подключить дополнительный репозиторий MySQL:
```
apt-key adv --keyserver pgp.mit.edu --recv-keys 5072E1F5
sh -c 'echo "deb http://repo.mysql.com/apt/debian/ stretch mysql-5.7" >> /etc/apt/sources.list.d/mysql.list'
```

Обновить список пакетов:
``` 
apt-get update
```

Установить любой пакет из этого репозитория:
```
apt-get install mysql-server-5.7
```