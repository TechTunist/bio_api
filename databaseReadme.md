# 7 minutes in 2.105

```bash
# initdb: warning: enabling trust authentication for local connections
# You can change this by editing pg_hba.conf or using the option -A, or
# --auth-local and --auth-host, the next time you run initdb.


# Success. You can now start the database server using:
    /usr/lib/postgresql/14/bin/pg_ctl -D /home/tunist/Django/api/django_databases/ -l logfile start
 
# to begin the postgres service again, use:
     sudo service postgresql start

 # to stop the postgres service, use:
         sudo service postgresql stop

# To log in to the default admin database that holds user information etc (postgres database) use:
    /usr/lib/postgresql/14/bin/psql -h localhost -d postgres

#Or just use:
    psql -d postgres

CREATE DATABASE # creates a new database

# To connect to a new database, use '\c <database_name>'

# To clear the postgres terminal, use:
    \! clear

# To see all tables (details) use:
    \d
    
    # To see specific tables, add the name of the table after \d <table_name>:
        \d address
```


# If the system tries to login to the database using the role "tunist", use this command to switch user to "postgres":

```bash
    sudo -u postgres psql -d postgres
```

# The above command specifies both the database and the user to be "postgres" which is the default.
