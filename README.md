# DjangoにてREST APIを実装する



## バージョン

```
django 4.2
pytz
```


## first_rest_apiがadminプロジェクト

```
django-admin startproject first_rest_project
cd first_rest_project
pytyhon manage.py runserver
```

## apiフォルダ

```
python manage.py startapp api # apiフォルダを追加
```


## APIviewとは？

APIを構築する際に使用されるView、HTTPメソッドに応じて処理を記述する。
