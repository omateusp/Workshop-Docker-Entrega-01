run:
	@docker-compose build
	@echo "Buildando Containers Docker."
	@echo "Subindo Containers Docker."
	@docker-compose up -d

stop:
	@docker-compose kill
	@docker-compose stop
	@docker-compose down --rmi local
	@echo "Containers Docker foram parados e deletados."