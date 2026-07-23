.PHONY: install sync lint format test run shell up down build

tree:
	tree -a -L 10 -I ".venv|.*|__*|*.egg-info|htmlcov|"

up:
	docker compose up -d --build
	
down:
	docker compose down

build:
	docker compose build

logs:
	docker compose logs -f
