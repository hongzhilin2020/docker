FROM mattrayner/lamp:latest-1604-php7
MAINTAINER qiubin <qiubin_2003@qq.com>

RUN sed -i "s/bind-address\s\+=\s\+127.0.0.1/bind-address = 0.0.0.0/g" /etc/mysql/mysql.conf.d/mysqld.cnf

CMD ["/run.sh"]
