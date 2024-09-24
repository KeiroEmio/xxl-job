# 定义服务名
SERVICE=xxl-job-admin

pull:
	docker pull xuxueli/xxl-job-admin:2.4.1

up:
	docker compose up -d $(SERVICE)

down:
	docker compose down

remove:
	docker compose down --rmi all --volumes --remove-orphans

logs:
	docker compose logs -f $(SERVICE)
