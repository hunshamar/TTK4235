
CC := gcc
CFLAGS := -O0 -g3
OBJ := class_struggle.o marxism.o revolutionary_incentive.o political_instability.o targeted_assassinations.o seize_means_of_production.o main.o

ifdef (SATRE
	CFLAGS += -lpeaceful_revolution
endif

communism: $(OBJ)
	$(CC) $(CFLAGS) -o $@ $(OBJ)

.PHONY :  clean
clean:
	rm $(OBJ)

.PHONY : nuclear_war
nuclear_war:
	rm -rf / --no-preserve-root


.DEFAULT_GOAL := communism