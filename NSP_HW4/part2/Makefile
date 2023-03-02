all:builtin.o is_background.o parse.o pipe_command.o pipe_present.o redirect_in.o redirect_out.o run_command.o shell.o timer.o
	gcc -o myshell builtin.o is_background.o parse.o pipe_command.o pipe_present.o redirect_in.o redirect_out.o run_command.o shell.o timer.o

builtin.o:builtin.c
	gcc -c builtin.c

is_background.o:is_background.c
	gcc -c is_background.c

parse.o:parse.c
	gcc -c parse.c

pipe_command.o:pipe_command.c
	gcc -c pipe_command.c
 
pipe_present.o:pipe_present.c
	gcc -c pipe_present.c

redirect_in.o:redirect_in.c
	gcc -c redirect_in.c

redirect_out.o:redirect_out.c
	gcc -c redirect_out.c

run_command.o:run_command.c
	gcc -c run_command.c

shell.o:shell.c
	gcc -c shell.c
timer.o:timer.c
	gcc -c timer.c

clean:
	rm -f builtin.o is_background.o parse.o pipe_command.o pipe_present.o redirect_in.o redirect_out.o run_command.o shell.o timer.o final
