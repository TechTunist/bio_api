initdb: warning: enabling trust authentication for local connections
You can change this by editing pg_hba.conf or using the option -A, or
--auth-local and --auth-host, the next time you run initdb.

Success. You can now start the database server using:

    /usr/lib/postgresql/14/bin/pg_ctl -D /home/tunist/Django/api/django_databases/ -l logfile start
 
'sudo service postgresql stop' to stop the postgres service, and 'start' to begin the postgres service again.
'/usr/lib/postgresql/14/bin/psql -h localhost -d postgres' This command logs in to the database using the default postgres user
