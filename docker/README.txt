build :
    docker build ./docker #docker is folder docker
run:
    docker-compose up -d

stop:
    docker-compose down


accss main container:
    docker-compose exec lara_server bash
