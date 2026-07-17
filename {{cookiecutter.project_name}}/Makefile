.PHONY: install sync lint format test run shell up down build

up:
	docker compose -d up --build
	
down:
	docker compose down

build:
	docker compose -d build

logs:
	docker compose logs -f