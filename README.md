# Setup WordPress Development Environment With Docker

## Start 
```
docker-compose build
docker-compose up -d
```
Then change the owner of wp-content folder to www-data, 
```
sudo chown www-data:www-data wp-content
```
