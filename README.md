# Game using sockets

## Description
This is a tow player basic dice game developed using socket programming in C language. The server will wait for players to connect once two players join the game will be initiated. Once a player reaches the specified score the game ends.

## Usage
```bash
git clone https://github.com/amanptl/dice-game/
cd dice-game
gcc server.c -o server
gcc client.c -o client
./server
./client <port> (Run this in two terminals)
```

