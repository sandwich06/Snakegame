# Snake game

##Server Package

### sql file
I use a server to connect to database(Mysql), and import this file to create the table.

### Database configeration
My database configeration is in package Server, the file "DataBase.java". Before running Server.java, use your database user and password to replace the variable "dbUser" and "dbPassword" in "DataBase.java".

###Run Server
Run "Server.java"

##Start game
In client Package, Run "MainFrame.java" to start game
If you do not run "Server.java", players also can play but will get error message when you try to get the rank or upload scores.
