all:main.o lookup6.o shm_server.o lookup5.o
	gcc -o shm_client main.o lookup6.o
	gcc -o shm_server shm_server.o lookup5.o

main.o:main.c
	gcc -c main.c

lookup6.o:lookup6.c
	gcc -c lookup6.c

shm_server.o:shm_server.c
	gcc -c shm_server.c

lookup5.o:lookup5.c
	gcc -c lookup5.c

clean:
	rm -f main.o lookup6.o shm_server.o lookup5.o
