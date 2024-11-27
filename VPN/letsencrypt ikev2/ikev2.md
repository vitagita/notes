создаем сертификат для ikev2
certbot certonly --rsa-key-size 4096 --standalone --agree-tos --no-eff-email --email admin@pinspb.ru -d vpn.aiconet.ru

