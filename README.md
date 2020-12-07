# reverseShell_socket_C_language
The reverse shell - also called reverse tunnel - is a computer technique that redirects the input and output of a shell to a remote 
computer on a local computer, through a service capable of interacting between the two computers.
So in this C program I used the sockets to create a server and client such that the client sends a command line to the server then the server 
executes this command in the terminal and sends the result to the client automatically using the system call "dup2" ,and finaly the client 
prints that result .
