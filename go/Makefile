GO_VERSION = 1.16.13
TAG        = plugins.buf.build/just/testing

build:
	docker build \
	--tag $(TAG) \
	--build-arg goVersion=$(GO_VERSION) \
	.