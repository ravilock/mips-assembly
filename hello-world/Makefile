default:
	mips-linux-gnu-as hello.s -o hello.o
	mips-linux-gnu-gcc hello.o -o hello -nostdlib -static
	qemu-mips ./hello

clean:
	rm hello.o hello
