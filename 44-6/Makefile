all:server client attack

server:fifo_seqnum_server.c get_num.c error_functions.c 
	gcc fifo_seqnum_server.c get_num.c error_functions.c -o server

client:fifo_seqnum_client.c get_num.c error_functions.c 
	gcc fifo_seqnum_client.c get_num.c error_functions.c -o client

attack:attack.c get_num.c error_functions.c 
	gcc attack.c get_num.c error_functions.c -o attack
