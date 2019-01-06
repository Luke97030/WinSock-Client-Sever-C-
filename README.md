# WinSock Client/Sever C++
An application which was built by C++

Once launched the client should provide at least a standard console interface (cout/cin) supporting the following commands:
-grep [-v] remotefolder regex .exts
-drop
-connect address
-stopserver


E.g: 
   // grep.exe 
   // [-v]           verbose scan or not. You can omit it if you wanna do regular scan
   // .              folder path. If you just type . It will search the folder which contains your .exe files 
   // [Ww]ord        regular expression, searching the regular expression under path, and list report at the end 
   // .txt.cpp.hpp   file extensios, if you just type . It will take the defaule file extension which is .txt
1. grep [-v] . [Ww]ord .txt.cpp.hpp 


2. drop 
   - drop command allow you as a client who can disconnet with server, so the next client is able to connect with same server using connect ipAddress
 
3. connect address
   - allow client to choose which ip he wants to connect. 
   - allow server to change its current ip address, after server's ip changed the client need to reconnect with server using new ip address
   (You can find out available by typing: ipconfig in the command window)

4. stopserver 
   - terminate running server and client and close the both command windwos 

