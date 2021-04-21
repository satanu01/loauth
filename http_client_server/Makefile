## gcc -w httpclient.c -o httpclient -L/usr/lib -lssl -lcrypto
all: bhclient.c bhserver.c
	gcc -w bhclient.c -o bhclient1
	gcc -w bhclient.c -o bhclient2
	gcc -w bhserver.c -o bhserver

clean: 
	$(RM) bhclient1
	$(RM) bhclient2
	$(RM) bhserver