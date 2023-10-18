# QRKot

## Application for the Cat Charity Fund

### Description 

The Foundation collects donations for various targeted projects: for medical care, for setting up a cat colony in the basement, for food for abandoned cats - for any purpose related to the support of the feline population.

### Techs

* python
* fastapi
* uvicorn
* SQLAlchemy
* alembic
* pydantic

### Install 
`git clone https://github.com/zakharovvladimir/cat_charity_fund.git`<br>
`python -m venv venv`<br>
`source venv/Scripts/activate`

### How to use

`pip install -r requirements.txt`
`alembic upgrade head`
`uvicorn app.main:app --reload`<br>
Migrations: `alembic revision --autogenerate -m "Revision_1"`<br>
`127.0.0.1:8000`<br>
Docs:<br>
`127.0.0.1:8000/docs` - Swagger<br>
`127.0.0.1:8000/redoc` - ReDoc

### Author

Vladimir Zakharov // vladimir.zakharov.s@yandex.ru
