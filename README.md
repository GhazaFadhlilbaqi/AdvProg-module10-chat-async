# Advanced Programming Module 9 - Timer Future
### Muhammad Ghaza Fadhlilbaqi - 2306173321

## Original code, and how it runs
![](images/experiment1.png)
How to run chat: Set up 4 terminals
- 1 terminal will be used as the server, run 
```bash
cargo run --bin server
```
- 3 terminals will be used as the clients, run 
```bash
 cargo run --bin client
 ```
After running, we can see from the screenshot above that when a client sends a message, the message will be received by the server, and then the message will be distributed to all clients connected to the server, including the client that sent the message. This happens because every client that connects to the server will be remembered by the server, and the server will wait until one of those clients sends a message to the server to be shared with all the clients connected to it.
