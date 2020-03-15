# A Django Rest Framework Boilerplate

## What's inside it?

- [Django REST framework](https://www.django-rest-framework.org/) - A powerful and flexible toolkit for building Web APIs.
- [PostgresSQL](https://www.postgresql.org/) - The World's Most Advanced Open Source Relational Database.

## Up and running

- Clone this repository: `git clone git@github.com:rafaelsevla/DRF-Boilerplate.git your-project-name`;
- Remove `.git` directory or run `git remote rm origin`;
- Create a virtualenv `virtualenv -p python3 .venv`
- Start Virtualenv `source .venv/bin/activate`
- Install dependencies `pip install -r requirements`
- Apply all the migrations `python manage.py migrate`
- Run `python manage.py runserver` to develop on `http://localhost:8000`

## Install PostgreSQL with Docker

- Copy [this](https://github.com/rafaelsevla/docker-compose-files/blob/master/postgres.yml) file and named to docker-compose.yml
- Run docker-compose up -d

## License

- [MIT](https://github.com/rafaelsevla/lemons-app/blob/master/LICENSE) © [Rafael Costa](https://github.com/rafaelsevla)
