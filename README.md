# TruChat
Minor 1 project

## Runnig the program:
1. Clone the repo  ``` git clone https://github.com/himanshu06d/TruChat.git ```
2. Run the makefile command  ``` make Makefile compile ``` 

        -OR-
2.  Compile server.c  ``` gcc -Wall -g3 -fsanitize=address -pthread server.c -o server ```
    Then compile client.c ```gcc -Wall -g3 -fsanitize=address -pthread client.c -l sqlite3 -o client```

3. Open 3 terminals

    a) In first terminal ``` ./server 8888 ```

    b) In second terminal ``` ./client 8888 ```

    c) In third terminal ``` ./client 8888 ```


4. Now Enjoy chatting

> To see the chats in the database, open the folder in VScode install sqlite3 extension -> Right click on test.db 
> -> In the SQLite explorer click on run button in front of the table name


### Contributers :- 
Ayush Bansal
Sahil Bansal
Himanshu Dubey
Aditya Raj
### Under the mentorship of 
### Dr. Sunil Gupta sir

