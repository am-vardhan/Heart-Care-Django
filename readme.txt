Below are the pre-requisites to configure this project

     create virtual environment
        cmd: python -m venv <any_name> --> in my case it is heartenv

     install DJango
        cmd: pip install django

    install pillow
        cmd: pip install pillow

    install MySqlclient
        cmd: pip install mysqlclient

    Download and install mysqlserver with mysqlworkbench (if needed GUI)
    
    create Database in the name of "heart"

TO Run this project:
    cmd: python manage.py makemigrations
    cmd: python manage.py migrate
    cmd: python manage.py createsuperuser
        -> provide credenatials for admin access when prompts
    cmd: python manage.py runserver
        browse the project on localhost

        