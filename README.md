# Скрипт рестарта докеризированных приложений после перезагрузки сервера

В переменную среды **PROJECTS** добавить названия папок с проектами.    

Например:
```
export PROJECTS="project1 project2"
```

В переменную среды **PREFIX** добавить путь до директории с проектами на сервере.

Например:
```
export PREFIX="/opt/projects/"
```


Запускаем скрипт sh start_pr