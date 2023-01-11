<p align="center">
    Desenvolvendo uma aplicação WebApi com Flask.
</p>

### Comandos para migração usando flask db
````
Informar o arquivo que contém as configurações Flask.
$ set FLASK_APP=api.py   

$ activate 

Comando para iniciar as migrações
$ flask db init

Comando para gerar as migrações
$ flask db migrate   

Comando para executar a migração
$ flask db upgrade
````

### Tecnologias
- [x] Marchmallow
- [x] Flask
- [x] MySQL
- [x] Alembic Migration(venv)


#### Links uteis

[flask-sqlalchemy-config](https://flask-sqlalchemy.palletsprojects.com/en/2.x/config/)