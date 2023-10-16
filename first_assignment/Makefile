CXX = g++
CXXFLAGS = -Wall -Wextra -std=c++11

SRC = trab01.cpp
EXE = trab01

all: $(EXE)

$(EXE): $(SRC)
	$(CXX) $(CXXFLAGS) $< -o $@

clean:
	rm -f $(EXE)
	rm -f saida1.txt
	rm -f saida2.txt

.PHONY: all clean
