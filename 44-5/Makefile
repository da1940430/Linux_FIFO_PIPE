all:server client

server:fifo_seqnum_server.c get_num.c error_functions.c 
	gcc fifo_seqnum_server.c get_num.c error_functions.c -o server

client:fifo_seqnum_client.c get_num.c error_functions.c 
	gcc fifo_seqnum_client.c get_num.c error_functions.c -o client