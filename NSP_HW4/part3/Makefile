all:main.o lookup3.o fifo_server.o lookup2.o
	gcc -o fifo_client main.o lookup3.o 
	gcc -o fifo_server fifo_server.o lookup2.o

main.o:main.c
	gcc -c main.c

lookup3.o :lookup3.c
	gcc -c lookup3.c

fifo_server.o :fifo_server.c
	gcc -c fifo_server.c

lookup2.o:lookup2.c
	gcc -c lookup2.c

clean:
	rm -f main.o lookup3.o lookup2.o fifo_server.o final
