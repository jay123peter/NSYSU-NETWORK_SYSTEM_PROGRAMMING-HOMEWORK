all:main.o lookup9.o udp_server.o lookup5.o
	gcc -o udp_client main.o lookup9.o
	gcc -o udp_server udp_server.o lookup5.o

main.o:main.c
	gcc -c main.c

lookup9.o:lookup9.c
	gcc -c lookup9.c

udp_server.o:udp_server.c
	gcc -c udp_server.c

lookup5.o:lookup5.c
	gcc -c lookup5.c

clean:
	rm -f main.o lookup9.o udp_server.o lookup5.o
