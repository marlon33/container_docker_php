## Installation
Rename the folder "APPLICATION_NAME_FOLDER" to your favorite name
run the code ```sh cp .env.example .env``` 

```sh
APPLICATION_NAME=
APPLICATION_PORT=80
APPLICATION_NAME_FOLDER=APPLICATION_NAME_FOLDER

DB_PORT=3306
DB_DATABASE=
DB_USERNAME=
DB_PASSWORD=
TZ=America/Sao_Paulo

```

after that run the code ```sh docker-compose up -d --build```
