git clone https://github.com/tomoropy/my_app
docker-compose build
docker-compse run web rake db:create
docker-comose up -d