all:consumer.o producer.o
	gcc -o consumer consumer.o -lrt
	gcc -o producer producer.o -lrt

consumer.o:consumer.c
	gcc -c consumer.c -lrt
producer.o:producer.c
	gcc -c producer.c -lrt
clean:
	rm -f consumer.o producer.o final
