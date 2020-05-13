# FTP--Unix-System-Programming
File Transfer Protocol- RFC - 959

FTP stands for the File transfer protocol and is used to transfer files between an FTP server and another computer. In the past, FTP was much more common than it is today and was the dominant file transfer mechanism on the Internet. If you needed to transfer files between two computers, you would use FTP to do so. FTP is still very popular today when a service requires that a lot of files be hosted for other to people to download. FTP also tends to be faster than other contemporary methods of transferring files because it was designed to do so.

The File Transfer Protocol (FTP) is a standard network protocol used for the transfer of computer files between a client and server on a computer network. FTP is built on a client-server model architecture using separate control and data connections between the client and the server. File Transfer Protocol (FTP) is an application layer protocol which moves files between local and remote file systems. It runs on the top of TCP, like HTTP. To transfer a file, 2 TCP connections are used by FTP in parallel: control connection and data connection.



# Execution
Install java on your Ubuntu terminal or subsystem.

First run the server program by using the command: 
sudo java server.java

As we are using port 21 for FTP to run any port under 1024 we need root access as port 21 is a privileged port.  

Then run the client program by using the command:
java client.java

Then you can give commands to the programs on the client side.


For doubts or queries please mail: pncl123@gmail.com
