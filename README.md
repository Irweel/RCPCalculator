#RCP CALCULATOR

## Install guide:

1. Install rpcbind
2. Create a RCP folder in your computer.
3. Clone this repo in the RCP folder.
4. Enter to a terminal and run the commans "rpcinfo" to see if correctly installed.
5. To create a new proyect we can use "rpcgen -a -C archivo.x" (tom no hagas esto, no es necesario)
6. Edit "archivo_client.c" and "archivo_server.c"
7. Compile them with "make -f Makefile.archivo".



## How to use:

1. Open 2 terminals and both with RPC folder dir.
2. run "sudo ./calculate_server and enter your password
3. Check your ip with ifconfig, and in the second terminal run "sudo ./calculate_client IP". IP usually goes something like 192.168.0.1
4. Enter the values and the operation term


