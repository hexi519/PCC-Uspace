
SOURCES = $(wildcard ./*.cpp)
OBJECTS = $(SOURCES:.cpp=.o)

CCFLAGS += -fPIC

%.o: %.cpp
	$(CC) $(CCFLAGS) $(LDFLAGS) $< -c

all: $(OBJECTS)

clean:
	rm -f *.o pccclient pccserver
