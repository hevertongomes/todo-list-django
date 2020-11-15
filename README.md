# Django Todo List

## Como usar

Clonar no repositório: <https://github.com/hevertongomes/todo-list-django.git>

Configure o ambiente do projeto com [virtualenv](https://virtualenv.pypa.io) e [pip](https://pip.pypa.io).

```bash
$ virtualenv project-env
$ source project-env/bin/activate
$ pip install -r requeriments.txt

## Para rodar o projeto.

$ cd todo-list-django
$ python manage.py migrate
$ python manage.py runserver
```

## Sobre o projeto

Um projeto intermediário usando Django 3. Utilizando o conceito de rotas e o padrão de templates juntamente com a autenticação do django auth. Este app o usuário entra e se cadastra, cria um usuário. A partir daí pode criar suas tarefas a serem feitas.
