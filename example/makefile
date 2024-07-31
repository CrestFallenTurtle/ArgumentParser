CC := go
OPTION := build
BIN := example
SRC := main.go

compile:
	$(CC) $(OPTION) -o $(BIN) $(SRC)

clean: clean_binary 

clean_binary:
	-rm $(BIN)

dependencies:
	go get github.com/CrestFallenTurtle/ArgumentParser
	go get github.com/CrestFallenTurtle/notify_handler
	go get github.com/CrestFallenTurtle/Go-tools