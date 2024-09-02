all:
	g++ product.cpp -o product

dump:
	objdump -d product > product.asm

run:	product
	./product

clean:
	rm -f product product.am 
