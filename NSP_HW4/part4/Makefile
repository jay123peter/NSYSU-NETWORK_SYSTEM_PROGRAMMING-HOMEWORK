all:main.o lookup4.o msgq_server.o lookup2.o
	gcc -o msgq_client -fno-stack-protector main.o lookup4.o 
	gcc -o msgq_server -fno-stack-protector msgq_server.o lookup2.o

main.o:main.c
	gcc -c main.c

lookup4.o :lookup4.c
	gcc -c lookup4.c

msgq_server.o :msgq_server.c
	gcc -c msgq_server.c

lookup2.o:lookup2.c
	gcc -c lookup2.c

clean:
	rm -f main.o lookup4.o msgq_server.o lookup2.o final
