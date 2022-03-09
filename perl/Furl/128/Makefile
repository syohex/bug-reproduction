all:
	echo "hello"

.PHONY: build
build:
	docker build -t perl-test .

.PHONY: test
test:
	docker run --rm perl-test
