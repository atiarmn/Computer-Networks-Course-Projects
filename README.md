# Computer Networks Course Projects

Implemented an FTP Server, a local network with switches and routing tables, and a bigger network with routers and multicast groups in course of three distinctive projects using C++ language:  

* FTP Server: In this project, two different codes were executed, one as an FTP server which serves the requests of clients, and one as a client communicating with the server via socket. Lots of commands were defined for managing directories such as pwd, mkd (for creating a directory), cwd (same as cd in Unix), etc. besides some authentication commands for clients. 
* Switching: 
* Multicast: In this project, we designed a simple network containing 7 routers and 15 clients, three of which acted as group servers -the administrators of multicast groups. Distinct processes were executed for each of these components, and they communicated with each other by Pipes. Routers designed their routing tables based on group information and matched them with their ports, and clients used some controlling commands to join or leave multicast groups. Group servers were the ones who sent their packets globally to the members of their groups. The image below shows the schematic view of this network. 
https://github.com/moeinsh78/Computer-Networks-Course-Projects/blob/master/Multicast/network.JPG
