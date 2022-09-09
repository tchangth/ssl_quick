# ssl_quick
sometimes we just need to create a webserver with ssl quick
in this case I get the ssl cert from certbot by using certonly with webroot
in this example there are 2 parts of it:
the first part is really quick and dirty as you can read the docker-compose.yml
the second part is we may need to initialize more php modules or a2enmod more apache2 modules
create 3 sub-directories: code, logs, ssl
