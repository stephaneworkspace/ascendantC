asc: asc.o
	gcc -o a.out asc.o

asc.o: asc.c
	gcc -c asc.c

dylib: asc.o
	gcc -dynamiclib -undefined suppress -flat_namespace asc.o -o ../ascendant.dylib

dll: asc.o
	gcc -shared asc.o -o ../ascendant.dll

clean:
	rm -f a.out asc.o ../ascendant.dylib ../ascendant.dll