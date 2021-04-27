# Health.mine
A health data tracker app used for extracting information from EHR records

# GUI

- Django used
- Easy extraction and interpretation using GUI
- For running GUI execute:

```bash
python resume_parser/manage.py makemigrations
python resume_parser/manage.py migrate
python resume_parser/manage.py runserver
```

- Visit `127.0.0.1` to view the GUI


# Running app in Docker

- Install docker-compose
- Execute the following commands from the root of the project
    - Build our images

        `docker-compose build`

    - Starting our containers and services

        `docker-compose up -d`

- Visit `localhost:8080` in your browser to run the app

