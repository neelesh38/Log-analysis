# LOG ANALYSIS

This project is part of Full Stack Nanodegree 

Aim of this project is to print report based on data in database by using python(2.7.10) 
and postgresql

### How To Install<br>
1.Install [Vagrant](https://www.vagrantup.com/) and [VirtualBox](https://www.virtualbox.org/)<br>
2.Download or clone from github [fullstack-nandegree-vm repository](https://github.com/udacity/fullstack-nanodegree-vm)</br>
3.Now we got newsdata.sql in our vagrant directory and now we are good to go.</br>

### How to run<br>
1. change directory to vagrant directory then<br>
2. **vagrant up** command to run the vagrant on vm<br>
3. **vagrant ssh** to login into vm<br>
4. change directory to vagrant<br>
5. use command **psql -d news -f newsdata.sql** to load database<br>
    -use **\c** to connect to database="news"<br>
    -use **\dt** to see the tables in database<br>
    -use **\dv** to see the views in database<br>
    -use **\q** to quit the database<br>
6. use command **python log1.py** to run the programm<br>
