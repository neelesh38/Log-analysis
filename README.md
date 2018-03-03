LOG ANALYSIS
This project is part of Full Stack Nanodegree

Aim of this project is to print report based on data in database by using python(2.7.10) and postgresql

How To Install
1.Install Vagrant and VirtualBox
2.Download or clone from github fullstack-nandegree-vm repository
3.Now we got newsdata.sql in our vagrant directory and now we are good to go.

How to run
change directory to vagrant directory then
vagrant up command to run the vagrant on vm
vagrant ssh to login into vm
change directory to vagrant
use command psql -d news -f newsdata.sql to load database
-use \c to connect to database="news"
-use \dt to see the tables in database
-use \dv to see the views in database
-use \q to quit the database
use command python3 log1.py to run the programm