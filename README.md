# FilmTv
docker-compose -f docker-compose.yml build
docker-compose -f docker-compose.yml up -d
docker-compose -f docker-compose.yml exec film_tv_backend bash
composer install
