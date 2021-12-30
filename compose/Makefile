kong-postgres:
	COMPOSE_PROFILES=database KONG_DOCKER_TAG=kong:centos KONG_DATABASE=postgres docker-compose up -d

kong-dbless:
	docker-compose up -d

clean:
	docker-compose kill
	docker-compose rm -f
