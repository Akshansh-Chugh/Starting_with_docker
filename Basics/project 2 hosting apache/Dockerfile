FROM ubuntu:22.04
RUN apt update && apt install apache2 -y
EXPOSE 80
CMD ["apache2ctl","-D","FOREGROUND"]
