## Prerequisites
- JDK 1.8 or later
- Maven 3 or later
- MySQL 5.6 or later

## Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- MySQL
## Database
Here,we used Mysql DB 
MSQL DB Installation Steps for Linux ubuntu 14.04:
- $ sudo apt-get update
- $ sudo apt-get install mysql-server

Then look for the file :
- /src/main/resources/db.sql

- db.sql file contents all step for DB table creation commands.

history 
 mkdir vprofile
 2001  cd vprofile/
 2002  git clone https://github.com/devopshydclub/vprofile-project.git
 2003  ll
 2004  mv vprofile-project/ ../
 2005  ll
 2006  cd ..
 2007  rm -rf vprofile
 2008  ll
 2009  cd vprofile-project/
 2010  l
 2011  ll
 2012  cat .git/config 
 2013  git branch
 2014  git branch -a
 2015  cat .git/config 
 2016  git branch -a | grep -v HEAD | cut -d '/' -f3 | grep -v master
 2017  git branch -a | grep -v HEAD | cut -d '/' -f3 | grep -v master > /tmp/branches
 2018  cat /tmp/branches 

 2023  for i in  `cat /tmp/branches`; do  echo $i;done 
 2024  for i in  `cat /tmp/branches`; do git checkout $i;done 
 2025  git branch -a
 2026  git  push origin --all
