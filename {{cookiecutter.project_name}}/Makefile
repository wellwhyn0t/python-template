.PHONY: install sync lint format test run shell up down build

up:
	docker compose -f docker/docker-compose.yml up

down:
	docker compose -f docker/docker-compose.yml down

build:
	docker compose -f docker/docker-compose.yml build

logs:
	docker compose -f docker/docker-compose.yml logs -f