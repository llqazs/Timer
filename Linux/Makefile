# DO NOT DELETE THIS LINE -- make depend depends on it.


# Edit the lines below to point to any needed include and source paths
# Or to change the compiler's optimization flags
# Note please change the compiler's flag -std=c++0x according to your g++ version

PROJECT = Timer
INCDIR = ..
SRC = ..
OBJS = example.o\
	Timer.o

CC = g++
COMPILEFLAGS = -I $(INCDIR) -O0 -g3 -Wall -c -std=c++0x -fmessage-length=0

all: $(PROJECT)

$(PROJECT): $(OBJS)
	$(CC) $^ -o $@ 

%.o: $(SRC)/%.cpp
	$(CC) $< -o $@ -c $(COMPILEFLAGS)

clean:
	rm -f *.o $(PROJECT)
