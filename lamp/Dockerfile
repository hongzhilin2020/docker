FROM mattrayner/lamp:latest-1604-php7
MAINTAINER qiubin <qiubin_2003@qq.com>

USER root
RUN sed -i 's/VirtualHost/Vincent888/g' /etc/apache2/ports.conf
# RUN sed -i 's/\/var\/www\/html/\/var\/www\/html\/public/g' /etc/apache2/sites-available/000-default.conf

CMD ["/run.sh"]
