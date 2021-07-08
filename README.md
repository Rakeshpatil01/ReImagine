# ReImagine
Python Project for self development and self improvement
to run test cases:
    docker-compose run app sh -c "python manage.py test"
every time you change the model we need to migrate the changes and update the database:
    docker-compose run app sh -c "python manage.py makemigrations core"