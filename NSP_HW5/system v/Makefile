all:consumer.o producer.o
	gcc -o consumer consumer.o
	gcc -o producer producer.o
consumer.o:consumer.c
	gcc -c consumer.c
producer.o:producer.c
	gcc -c producer.c
clean:
	rm -f consumer.o producer.o final
