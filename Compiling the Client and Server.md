# Compiling the Client

1. Open the development VM.
2. Launch CodeWarrior.
3. Open Oberin.dms in CodeWarrior.
4. Click the green arrow play button in CodeWarrior.

# Compiling the Server
1. Uncomment ```#define _SERVER``` and ```#define _SERVERONLY``` in Globals.h
2. Follow the client instructions.

Note:
- There is a 0kb Oberin Server.rscs, it is likely corrupt and was likely used to swap the compilation from client to server to make things easier.
- A connection between a compiled client and server hasn't been established yet. It isn't fully understood if the server is fully functional in the repository.
