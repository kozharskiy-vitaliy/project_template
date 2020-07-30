FROM alpine
SHELL ["/bin/bash", "-c"]
RUN apt update \
&& apt upgrade \
&& apt-get install -y apt-utils php apache2 \ 
&& rm /var/www/html/index.html \
&& chmod 777 -R /var/www/

