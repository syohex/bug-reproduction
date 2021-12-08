all:
	echo "make server or make generate"

.PHONY: server

server:
	python -m http.server 8080

generate:
	perl -MData::MessagePack -E 'say Data::MessagePack->pack( { a => 1, b => 2 } )' > msg.bin
