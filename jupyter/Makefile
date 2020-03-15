build-base:
	docker build -t jupyterlab:base -f .docker/Dockerfile.base .

# run this if you update the requirements.txt
build-extend:
	docker build -t jupyterlab:extend -f .docker/Dockerfile.extend .

# run on first-time to build the images
build:
	make build-base build-extend

# start the lab
lab:
	docker-compose up
