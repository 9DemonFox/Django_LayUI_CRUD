# 觉得有用请点赞

## 1. 使用sqlite作为数据库，则不需要配置mySQL
```
参考settings
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.sqlite3',
        'NAME': os.path.join(BASE_DIR, 'student_crud'),
    }
}
```
## 2. 开始使用
> pycharm cmd
```
python manage makemigrations
python manage migrate
```
> windows cmd(命令行)
```
python .\manage.py makemigrations
python .\manage.py migrate
```

