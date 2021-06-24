PWD=$(shell pwd)

build:
	protoc \
	-I$(PWD) \
	--java_out=. \
	--swagger_out=logtostderr=true:. \
	--swagger_opt allow_delete_body=true \
	common.proto;
