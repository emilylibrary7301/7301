# mysql logged in as [(none)]>

If you logged into a mysql database and your showing [(none)]> as the command line and you want the command line to read mysql>, the fix is super easy!

**Exit out of mysql**

\q;

**Add sudo at the beginning of your command**

sudo mysql -u database_name -p

**Enter password**

You should now see mysql> at the beginning of your command line
