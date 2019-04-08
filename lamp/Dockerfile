FROM mattrayner/lamp:latest-1604-php7
MAINTAINER qiubin <qiubin_2003@qq.com>

# RUN sed -i "s/# You can copy this to one of:/# vincent is good/g" /etc/mysql/my.cnf
RUN sed -i 's/\/var\/www\/html/\/var\/www\/html\/public/g' /etc/apache2/sites-available/000-default.conf

CMD ["/run.sh"]
