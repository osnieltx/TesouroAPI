# PythonServer

1. Instalação do PostgreSQL
    1.1 Mac -> Via HomeBrew
    No terminal:
        virtualenv env (dentro da pasta do projeto)
        source env/bin/activate
        brew update
        brew install postgres
        postgres -D /usr/local/var/postgres
        createdb 'historico'
        pip3 install psycopg2