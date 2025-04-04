all: p2 test

p2: p2.c funciones.c funciones.h
	@gcc -o p2.out -Wall p2.c funciones.c funciones.h -lm
	
clear_p2:
	@rm *.out
	
	
test: test.c funciones.c funciones.h
	@gcc -o test.out -Wall funciones.c funciones.h test.c -lm
	
clear_test:
	@rm *.out
