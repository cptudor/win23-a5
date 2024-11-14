objects = main.o addition.o subtraction.o multiplication.o division.o

calculator: $(objects)
	cc -o calculator $(objects)
#	cc -o calculator $^

#$(objects): %.o:%.c
#	cc -c $< -o $@

#main.o: operations.h

clean:
	rm -f calculator $(objects)
