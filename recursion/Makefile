CXX = clang++ -std=c++14

OPT = -Ofast

all: recursion queue-recursion mutual-recursion

recursion: recursion.C
	$(CXX) $(OPT) $@.C -o $@

queue-recursion: queue-recursion.C
	$(CXX) $(OPT) $@.C -o $@

mutual-recursion: mutual-recursion.C
	$(CXX) $(OPT) $@.C -o $@

clean:
	$(RM) *~ recursion queue-recursion mutual-recursion
