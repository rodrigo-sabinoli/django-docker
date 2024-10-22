# Django com docker-compose

## 1- Criar um arquivo docker-compose

## 2- Para iniciar um projeto 
```console
django docker-compose run web django-admin startproject {NOME DO PROJETO} .
```
## 3- Para criar um app django
    
```console
docker-compose run web python manage.py startapp {NOME DO APP}
```

## 4- Para rodar o projeto 
```console
docker-compose up -d --build
```
    