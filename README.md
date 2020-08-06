# oracle

issue 
chown: invalid user: `oracle:oinstall'


As root, run the following commands to create the Oracle user and groups:

# groupadd dba
# groupadd oinstall
# useradd -m -g oinstall -G dba oracle
