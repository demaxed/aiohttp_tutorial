# aiohttp

https://aiohttp-demos.readthedocs.io/en/latest/tutorial.html

    python -m aiohttpdemo_polls

![alt-текст](https://pp.userapi.com/c846420/v846420931/1ee3a5/KKaGRPdgo-g.jpg)

### PostgreSQL

    sudo -u postgres psql
    postgres=# create database aiohttpdemo_polls;
    postgres=# create user aiohttpdemo_user with encrypted password 'aiohttpdemo_pass';
    postgres=# grant all privileges on database aiohttpdemo_polls to aiohttpdemo_user;  
    python init_db.py

### Creating connection egine

For making DB queries we need an engine instance.

### Templates

Templates are a very convenient way for web page writing. If we return a dict with page content, the aiohttp_jinja2.template decorator processes the dict using the jinja2 template renderer.