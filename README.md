# WEB

#### dir
List directories.

#### cd
Change directory.

#### mkdir
Make directory.

#### rmdir
Remove directory.

#### cd ..
Move up to parent folder.

#### exit()
Exit python terminal.

# PYTHON PROJECTS

## create a virtual environment
python3 -m venv environment  
source env/bin/activate  
pip install Flask  

#### python3 -m venv env
Creates an environment to isolate packages.

#### source env/bin/activate
Gets the package folder

#### pip
Shows package commands

# RUNNING Flask

#### export/set
In windows, export is 'set', whereas it is 'export' in mac.

#### install flask

pip install flask

#### run flask

cd (to directory)  
source env/bin/activate    
set FLASK_APP=run.py  
set FLASK_DEBUG=1  
flask run

# SQL Lite

#### sqlite ____.db

creates a database  
*"sqlite menu.db"*

#### dot commands
.tables *(shows tables)*

.headers on  
.mode column  
.width 5 30 10

#### creating tables
CREATE TABLE burgers (  
id INTEGER PRIMARY KEY  
burger TEXT  
price FLOAT );

INSERT INTO burgers(burger, price) VALUES ('Classic Burger', 4.99);

#### DROP TABLE
removes table

#### SELECT * FROM

#### UPDATE SET WHERE
