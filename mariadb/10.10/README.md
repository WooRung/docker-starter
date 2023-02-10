# How to run

`sudo docker run --name mariadb-1 -v ${PWD}/data:/var/lib/mysql -v ${PWD}/conf.d:/etc/mysql/conf.d -v ${PWD}/log:/var/log --env-file .env mariadb:10.10.2`
