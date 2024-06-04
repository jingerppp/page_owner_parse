test: test.o parse_base.o
	g++ -o $@ $^

%.o: %.cpp
	g++ -c $< -I ./ -o $@ -Wall

clean:
	rm -f *.o
	rm -f test
