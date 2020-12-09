### Дамп БД в Django
python3.8 manage.py dumpdata --natural-foreign --exclude auth.permission --exclude contenttypes --indent 4 > dump.json
#### загрузка в БД
python3.8 manage.py loaddata data.json

#### доступ к /dev/ttyUSB0
* sudo usermod -a -G tty username 
* udo usermod -a -G dialout username
* перелогинится
