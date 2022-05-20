Initializing:

1) install requirements (todo - reduce requirements to minumim)
2) install postgres - brew install postgresql
3) brew services start postgresql
4) initdb /usr/local/var/postgres
   createuser student --createdb 
5) createdb studentdb --encoding='utf-8'
   Run create_tables.py
6) optional: psql sparkifydb -U student
