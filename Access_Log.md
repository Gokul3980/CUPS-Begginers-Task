# ADDING COMMENTS AND PRINTING THEM
Here first we commented in the log.c file which was present in the scheduler folder of the cups repo. Then we re-built it i.e., cups by using the commands "make" and "sudo make install". Then we moved to the particular directory and took a screenshot of the modified access log.

## Here is modified accesslog
```
localhost - - [31/Dec/2022:00:28:40 +0530] "POST / HTTP/1.1" 200 349 Create-Pri>
localhost - - [31/Dec/2022:00:28:40 +0530] "POST / HTTP/1.1" 200 176 Create-Pri>
localhost - - [31/Dec/2022:00:28:43 +0530] "POST / HTTP/1.1" 200 359 Create-Pri>
localhost - - [31/Dec/2022:00:29:36 +0530] "POST / HTTP/1.1" 200 361 Create-Pri>
localhost - - [31/Dec/2022:00:29:38 +0530] "POST / HTTP/1.1" 200 151 Cancel-Sub>
localhost - - [31/Dec/2022:00:34:06 +0530] "POST /admin/ HTTP/1.1" 401 238 CUPS>
localhost - gokul [31/Dec/2022:00:34:06 +0530] "POST /admin/ HTTP/1.1" 200 238 >
localhost - - [31/Dec/2022:00:35:22 +0530] "POST /admin/ HTTP/1.1" 401 238 CUPS>
localhost - gokul [31/Dec/2022:00:35:22 +0530] "POST /admin/ HTTP/1.1" 200 238 >
localhost - - [31/Dec/2022:00:35:41 +0530] "POST /printers/testP HTTP/1.1" 200 >
localhost - - [31/Dec/2022:00:35:41 +0530] "POST /printers/testP HTTP/1.1" 200 >
localhost - - [03/Jan/2023:18:50:22 +0530] "POST / HTTP/1.1" 200 349 Create-Pri>
localhost - - [03/Jan/2023:18:50:22 +0530] "POST / HTTP/1.1" 200 176 Create-Pri>
localhost - - [03/Jan/2023:18:50:27 +0530] "POST / HTTP/1.1" 200 359 Create-Pri>
localhost - - [03/Jan/2023:18:50:36 +0530] "POST / HTTP/1.1" 200 361 Create-Pri>
localhost - - [03/Jan/2023:18:50:38 +0530] "POST / HTTP/1.1" 200 151 Cancel-Sub>
localhost - - [03/Jan/2023:18:50:38 +0530] "POST / HTTP/1.1" 200 151 Cancel-Sub>
localhost - - [03/Jan/2023:18:51:44 +0530] "POST /admin/ HTTP/1.1" 401 239 CUPS>
localhost - gokul [03/Jan/2023:18:51:44 +0530] "POST /admin/ HTTP/1.1" 200 239 >
localhost - - [03/Jan/2023:18:52:20 +0530] "POST /printers/testpr HTTP/1.1" 200 >
localhost - - [03/Jan/2023:18:52:20 +0530] "POST /printers/testpr HTTP/1.1" 200>
 Gokul Goyal commented here
 localhost - - [03/Jan/2023:18:57:24 +0530] "POST /admin/ HTTP/1.1" 401 240 CUP>
 Gokul Goyal commented here
 localhost - gokul [03/Jan/2023:18:57:24 +0530] "POST /admin/ HTTP/1.1" 200 240>
 Gokul Goyal commented here
 localhost - - [03/Jan/2023:18:57:43 +0530] "POST /printers/nowhere HTTP/1.1" 2>
 Gokul Goyal commented here
 localhost - - [03/Jan/2023:18:57:43 +0530] "POST /printers/nowhere HTTP/1.1" 2>
```
