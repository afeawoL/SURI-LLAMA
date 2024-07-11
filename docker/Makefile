docker-build:
	docker compose build

docker-run:
	docker compose up --detach

docker-stop:
	docker compose down

docker-shell-pt:
	docker exec -it star_pt bash

docker-shell-tf2:
	docker exec -it star_tf2 bash

docker-vscode:
	docker exec -d -it star_pt code-server --bind-addr 0.0.0.0:8443 --auth password --disable-telemetry /notebooks
	docker exec -d -it star_tf2 code-server --bind-addr 0.0.0.0:8443 --auth password --disable-telemetry /notebooks
