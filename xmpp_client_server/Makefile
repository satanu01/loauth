## gcc -w httpclient.c -o httpclient -L/usr/lib -lssl -lcrypto
all: xmppclient.c xmppserver.c
	gcc -w xmppclient.c -I/usr/include/libxml2 -lxml2 -o xmppclient1
	gcc -w xmppclient.c -I/usr/include/libxml2 -lxml2 -o xmppclient2
	gcc -w xmppserver.c -I/usr/include/libxml2 -lxml2 -o xmppserver

clean: 
	$(RM) xmppserver
	$(RM) xmppclient1
	$(RM) xmppclient2
	
#run:
#	./xmppserver
#	./xmppclient1 satanu@localhost pub 10
