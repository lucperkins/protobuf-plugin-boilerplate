PREFIX         =  plugins.buf.build
GO_VERSION     =  1.16.13
OWNER          =  lucperkins
NAME           =  testing
PLUGIN         = $(OWNER)/$(NAME)
PLUGIN_VERSION =  v0.1.0
TAG            := $(PREFIX)/$(PLUGIN):$(PLUGIN_VERSION)

build:
	docker build \
	--tag $(TAG) \
	--build-arg goVersion=$(GO_VERSION) \
	$(CURDIR)

push:
	docker push $(TAG)