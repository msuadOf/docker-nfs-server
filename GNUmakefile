REPOSITORY = ghcr.io/msuadof
IMAGE = $(REPOSITORY)/nfs-server

all: image

image:
	DOCKER_BUILDKIT=1 \
	docker build --no-cache --tag $(IMAGE):latest .

.PHONY: all image
