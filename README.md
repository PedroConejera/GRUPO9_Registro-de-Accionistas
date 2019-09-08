# Administrador de Registros de Accionistas
Proyecto universitario llevado a cabo en Django. 
[Tablero del Proyecto en Trello](https://trello.com/b/BP7z3o5H/grupo9registro-de-accionistas)

## Dependencies
Create _**requirements.txt**_ and put in it the text below
**Docker and Docker-compose needed**
```text
django>=2.1
djangorestframework
gunicorn
psycopg2
```

## Usage
Installation (for local tests): 
```shell
pip3 install -r requirements.txt
pip3 install virtualenv
virtualenv venv
cd venv/Scripts/
activate.bat
```

Run:
```docker-compose
docker-compose run web python manage.py makemigrations
docker-compose run web python manage.py migrate
docker-compose run web python manage.py createsuperuser
docker-compose up
```

## Authors
* **Pedro Conejera** - *2019* - [PedroConejera](https://github.com/PedroConejera)
* **Gonzalo Manquilef** - *2019* - [Noygan](https://github.com/Noygan)
* **Ronaldo Cavero** - *2019* - [Jcvron](https://github.com/jcvron)
* **Francisco Vargas** - *2019* - [Tostin](https://github.com/Tostin)
* **Agustín Sepúlveda** - *2019* - [Dreeakonee](https://github.com/Dreeakonee)
* **Oscar Edding** - *2019* - [OscarEdding](https://github.com/OscarEdding)
