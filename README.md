# jade-asterisk
Jade project on a docker with the Asterisk.

# RUN
$ docker run -d \
  -p 80:80/tcp \
  -p 443:443/tcp \
  -p 8081-8089:8081-8089/tcp \
  -p 8081-8089:8081-8089/udp \
  -p 8200-8203:8200-8203/tcp \
  -p 8200-8203:8200-8203/udp \
  -p 5060:5060/tcp \
  -p 5060:5060/udp \
  -p 10000-10500:10000-10500/udp \
  --name jade-asterisk \
  -t jade-asterisk

