# mysql-daily-backup
Here, I have provide a script for linux machine. It is a bash script.

We can use this simple script to automate the backup process of mysql database. We have to specify the username, password and the database we want to backup on the script along with the mysql server ip.
I have declared some variables in the script to make it easy to reuse the script, but it can be run without the variables also. In the end of the script we have zipped the backup file and moved to our desire directory. \

I have use date on the name so that it will easier to find a backup file of specific date.

We can automate the task and schedule it daily we can use cronjob. it is a free tool for task scheduling in linux.
