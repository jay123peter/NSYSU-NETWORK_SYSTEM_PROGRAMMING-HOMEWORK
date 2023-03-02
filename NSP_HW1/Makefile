all:parse.o shell.o builtin.o run_command.o is_background.o
	gcc parse.o shell.o builtin.o run_command.o is_background.o -o final
parse.o:parse.c
	gcc -c parse.c
shell.o:shell.c
	gcc -c shell.c
builtin.o:builtin.c
	gcc -c builtin.c
run_command.o:run_command.c
	gcc -c run_command.c
is_background.o:is_background.c
	gcc -c is_background.c
clean:
	rm -f parse.o shell.o builtin.o run_command.o is_background.o final
