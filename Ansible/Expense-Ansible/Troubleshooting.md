DB
------
> systemctl status mysqld --> Check mysql service is running or not
> netstat -lntp --> Check port no 3306 is opened or not
> mysql -h db.nagacharan.site -u root -pExpenseApp@1

> ps -ef | grep mysql --> mysql services runing or not

backend :
-------
> systemctl status backend
> netstat -lntp --> check 8080 running or not
> telnet db.nagacharan.site 3306 --> Check you are able to connect mysql or not

> mysql -h db.nagacharan.site -u root -pExpenseApp@1

show databases;
use transactions;
show tables;

> ps -ef | grep expense 

frontend :
----------
> systemctl status nginx

> netstat -lntp

> telnet backend.nagacharan.site 8080

