creating crontab file in AWS

create new instance 
(for windows)
connect to it via putty in windows by creating .pem file in puttyGen

create a py script and a .cron script to run in some specific interval 
- nano filename.py
- nano filename.cron

add the .cron file in crontab 
- crontab filename.cron

to view 
- crontab -l

to remove 
- crontab -r
