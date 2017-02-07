**Docker - Sylius**

_NGINX-PHP FPM-MYSQL_

Clone this repository or place _docker-compose.yml_ file and _docker_ folder inside the Sylius root directory.

Then, run

```bash

$ docker-compose up -d

_Install the dependencies _

$ docker exec -it sylius_php composer install

adjust the _parameters.yml_

Install sylius

$ docker exec -it sylius_php php bin/console sylius:install

$ docker exec -it sylius_php npm install

$ docker exec -it sylius_php npm run gulp

open _http://localhost:8080/app_dev.php_


```





 
 





