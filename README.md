# Hello World

Hello World!

I am TheRocker7421, here to bring you my first project, Hello World! I have made a Hello World program for Linux that displays "Hello World!" for 5 seconds!

# Compiling

To compile the code, please make sure that you have g++ and libsdl2-dev installed. You can easily install this on Debian/Ubuntu by typing this code in the terminal.

```
sudo apt install g++ libsdl2-dev
```

Then, type 
```
g++ helloworld.cpp -w -lSDL2 -o helloworld
```
in the terminal. Then all you have to do is type

```
./helloworld
```
to run it. **Alternative: You can use the Makefile provided to build the project. Just type make in the terminal and make will do the rest.**
