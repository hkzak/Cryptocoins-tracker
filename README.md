# Cryptocoins-tracker
This Django App keeps track of the latest Crypto currencies price value

Requirements:
Install Python 3.7
Install Django
Install celery / redis


How to get it to work :
- Start a redis server using commat "redis-sever" then hit enter, to able to do that you need to open a terminal with WSL enabled or open the project with WSL.
- start the django app using "pyhton3 manage.py runserver" cd to /app/cmc_project/
- Start the celery beat worker using "celery -A cmc_project beat -l INFO"
- Start the celery worker using "celery -A cmc_project worker -l INFO"

![crypto-tracker](https://user-images.githubusercontent.com/22933014/168347180-b21c54df-02bf-43d8-a535-cd86e0ae8978.PNG)
