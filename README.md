## Passo a passo para você iniciar um projeto com o framework django-rest

### Criar um ambiente isolado é extramemente importante caso você esteja trabalhando em vários projetos diferentes, por isso o primeiro passo é criar um ambiente virtual.

> - python -m venv venv 

### O ambiente virtual faz o envelopamento das bibliotecas que você estará utilizando nesse projeto.
### Para entrar no ambiente virtual você deve executar o seguinte comando:

> #### No windows:
> - . venv/Scripts/activate 
>
> #### No Linux:
> - . venv/bin/activate
 
### Com a VENV ativa basta instalar o Django

> - pip install django
 
### Crie seu projeto

> - django-admin startproject +NomeDoProjeto .
> - python manage.py migrate

### Instale o Django-Rest

> - pip install djangorestframework
> não esqueça de registrar o rest_framework no settings da aplicação


### Para criar um app execute o comando:
> - python manage.py startapp +NomeDoApp

### Para executar seu projeto:
> - python manage.py runserver

### Para criar um super usuário:
> - python manage.py createsuper
