
# Socket Programming

##Team Members:-
  #a.Lavish Gupta(B21AI024)
  #b.Abhishek Arya(B21AI002)

# #Client-Server Chat System
##This is a simple client-server chat system built in C. The client can chat with a "math" server, where the server evaluates arithmetic expressions and sends back the result it got to the client.
# #How to Run
## #Server 1 (Single Process Server)

##To run the single process server, navigate to the root directory and run the following command in the terminal:

#$ gcc server1.c -o server1
#$ ./server1 <port_number>(in our case it is 8080)

#The server will start running and listening for client requests on the specified port number.

## #Server 2 (Multi-process/Multi-threaded Server)

##To run the multi-process/multi-threaded server,it would navigate to the root directory and run this following command in the terminal:

#$ gcc multiserver2.c -o server2 -lpthread

#$ ./server2 <port_number>(it is 8080).

##The server will start running and listening for multiple client requests on the specified port number.

## #Client

##To run the client, navigate to the root directory and run the following command in the terminal as following:


#$ gcc client.c -o client

#$ ./client <server_IP> <port_number>(it is 8080).

#Replace <server_IP>(it is 127.0.0.1) with the IP address of the server you want to connect to, and <port_number> with the port number the server is listening on. The client will then establish a connection with the server and prompt you to enter an arithmetic expression(like:+,-,*,%). The server will evaluate the expression and send back the result, which will be displayed by the client. 
#Continue chatting with the server by entering more expressions, until and unless,the program terminate the client program by pressing Ctrl+C.

## #Supported Operations
##The servers support addition, multiplication, subtraction, and division operations on two integer operands,client provide. The two operands should be separated by a space.

## #Credits
##This project was completed as part of an Socket assignment for PCS-II. The client code was provided, and the server codes was written by Lavish Gupta(B21AI002) and Abhishek Arya(B21AI002)








