### Дамп БД в Django
python3.8 manage.py dumpdata --natural-foreign --exclude auth.permission --exclude contenttypes --indent 4 > dump.json
#### загрузка в БД
python3.8 manage.py loaddata data.json
