# aiohttp

https://aiohttp-demos.readthedocs.io/en/latest/tutorial.html

    python aiohttpdemo_polls/main.py


### PostgreSQL

    sudo -u postgres psql
    postgres=# create database aiohttpdemo_polls;
    postgres=# create user aiohttpdemo_user with encrypted password 'aiohttpdemo_pass';
    postgres=# grant all privileges on database aiohttpdemo_polls to aiohttpdemo_user;  
    python init_db.py
