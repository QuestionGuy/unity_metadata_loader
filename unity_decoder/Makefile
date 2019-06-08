CC=g++
CXXFLAGS=-g
INCLUDES="libil2cpp"
OUT=il2cpp_dumper

$(OUT): main.o
	$(CC) main.o -o $(OUT)

main.o: main.cpp
	$(CC) $(CXXFLAGS) -I$(INCLUDES) -c main.cpp -o main.o

clean: 
	rm -rf *.o $(OUT)
