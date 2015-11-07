CFLAGS=-g 

all: myAllocatorTest1.exe test1.exe

myAllocatorTest1.exe: myAllocator.o myAllocatorTest1.o
	gcc -o myAllocatorTest1.exe -g myAllocator.o myAllocatorTest1.o

test1.exe: myAllocator.o malloc.o test1.o
	gcc -o test1.exe -g myAllocator.o malloc.o test1.o
clean:
	rm -f *.o *.exe

