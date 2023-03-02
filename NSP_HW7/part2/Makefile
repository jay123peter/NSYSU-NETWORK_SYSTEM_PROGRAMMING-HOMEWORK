all:main.o lookup8.o isock_server.o lookup5.o
	gcc -o isock_client main.o lookup8.o
	gcc -o isock_server isock_server.o lookup5.o

main.o:main.c
	gcc -c main.c

lookup8.o:lookup8.c
	gcc -c lookup8.c

isock_server.o:isock_server.c
	gcc -c isock_server.c

lookup5.o:lookup5.c
	gcc -c lookup5.c

clean:
	rm -f main.o lookup8.o isock_server.o lookup5.o
