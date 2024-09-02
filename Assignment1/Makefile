all:
	g++ simpleint.cpp -o simpleint
dump:
	objdump -d simpleint > simpleint.asm
run: simpleint
	./simpleint
clean:
	rm -f simpleint simpleint.asm 

