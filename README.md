0. Clone this repository into /var/www/detwitch
1. Install all the configuration files
2. Get certificates with certbot
3. Symlink `ln -sT /tmp/hls /var/www/detwitch/hls/hls`
4. `nginx -t && systemctl restart nginx`
5. Enjoy! :3
