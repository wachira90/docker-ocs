# docker-ocs
docker ocs

## create folder

mkdir ocsdata ocsreports ocslib ocsconfig

## permission 

chmod -R 777 ocsdata ocsreports ocslib ocsconfig

## run

docker compose up -d

## URL

user: admin

pass: admin

localhost:8011/ocsreports

## FIX 

copy config

docker cp ocsinventory:/etc/opt/remi/php73/php.ini .



