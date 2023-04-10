FROM nginx

RUN apt install libnginx-mod-http-geoip geoip-database
RUN mkdir /usr/share/GeoIP
RUN cd /usr/share/GeoIP
RUN wget https://centminmod.com/centminmodparts/geoip-legacy/GeoIP.dat.gz
RUN gunzip GeoIP.dat.gz
