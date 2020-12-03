# ioc-sign-up-app-v2

This repo has been created based on the sign-up app created in the [working-with-flask](https://github.com/IoC-Sunderland/working-with-flask-forms) repo.

The app has been ported to Django, a Postgres db connection has been configured and app deployed to Heroku.

Heroku provides a free Postgres instance we can use for small projects, the use of an sqlite database is not recommended as it will not persist
on Heroku as the filesystem is ephemeral.

