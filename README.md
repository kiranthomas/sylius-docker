Docker - Sylius

NGINX-PHP FPM-MYSQL

Clone this repository or place docker-compose.yml file and docker folder inside the Sylius root directory.

Then, run

docker-compose up -d

Install the dependencies 

docker exec -it sylius_php composer install

adjust the parameters to connect to db

Install sylius dev

docker exec -it sylius_php php bin/console sylius:install

docker exec -it sylius_php npm install

docker exec -it sylius_php npm run gulp

visit http://localhost:8080/app_dev.php



 
 





