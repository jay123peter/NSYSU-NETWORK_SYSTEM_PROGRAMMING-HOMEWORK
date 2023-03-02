all:main.o lookup7.o usock_server.o lookup5.o
	gcc -o usock_client main.o lookup7.o 
	gcc -o usock_server usock_server.o lookup5.o
	
main.o:main.c
	gcc -c main.c

lookup7.o:lookup7.c
	gcc -c lookup7.c
	
usock_server.o:
	gcc -c usock_server.c
		
lookup5.o:lookup5.c
	gcc -c lookup5.c
	
clean: 
	rm -f *.o usock_client usock_server TUNNEL
