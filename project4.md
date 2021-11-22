[Back to Portfolio](./)

UDP Client and Server
===============

-   **Class: CSCI 332** 
-   **Grade: 100**
-   **Language(s): C++, C**
-   **Source Code Repository:** [HMAckerman/APPNTWRKProject](https://github.com/HMAckerman/APPNTWRKProject)  
    (Please [email me](mailto:HMAckerman@csustudent.net?subject=GitHub%20Access) to request access.)

## Project description

This project is a mix of two programs, one being the client that sends UDP packets and the other being the server that receives the UDP packets. This program implements the C++ networking library, utilizing system-based sockets and ports, along with the capability to send files . First, the user compiles and runs the UDPClient.cpp, and then the user opens a new terminal and runs UDPServer.cpp. In doing so, this sets up the two programs to receive input from the user. Then, the client asks the user for the IP address of the server, the port it is listening on, and the name of the file to transfer. The server is currently in a waiting state, and asks the user for the port it should listen on. Once the client and the server exchange a full conversation of data, the server will say "Successfully received all bytes!", and will stay in a waiting state if the user wishes to send more data. 

## How to compiles / run the program

How to compile (if applicable) and run the project.

```bash
cd /project4
python setup.py
```

## UI Design

Lorem ipsum dolor sit amet (see Fig 1), consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat (see Fig 2). Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum (see Fig 3).

![screenshot](images/dummy_thumbnail.jpg)
Fig 1. The launch screen

![screenshot](images/dummy_thumbnail.jpg)
Fig 2. Example output after input is processed.

![screenshot](images/dummy_thumbnail.jpg)
Fig 3. Feedback when an error occurs.

## 3. Additional Considerations

This was an exercise in which the C++ networking library was utilized. Admittedly, I had never used the networking library before, so this was a great learning experience.   

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

[Back to Portfolio](./)
