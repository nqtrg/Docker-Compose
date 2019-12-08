build-base:
	docker build -t jupyterlab:base -f Dockerfile.base .

build-extend:
	docker build -t jupyterlab:extend -f Dockerfile.extend .

build:
	make build-base build-extend

lab:
	docker-compose up