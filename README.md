# symfony5.2-php8


```
git clone git@github.com:drochette/symfony5.2-php8.git

cd symfony5.2-php8

cd infra

docker-compose up -d --build

docker-compose run php composer create-project symfony/skeleton:"5.2.x@dev" .
