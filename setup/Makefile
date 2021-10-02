.PHONY: all1 all clean say_hello generate clean_files
CFLAGS=-Wall -g
all1: say_hello generate 
all:
	@cc -Wall -g ex1.c -o ex1
clean:
	@rm -f ex1
say_hello:
	@echo "Hello World"
generate:
	@echo "Creating empty text files..."
	touch file-{1..10}.txt
clean_files:
	@echo "Cleaning up..."
	rm *.txt
