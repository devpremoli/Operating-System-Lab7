TASK1_SRC := mmu.c util.c list.c
EXE := mmu

all: $(EXE)

$(EXE): $(TASK1_SRC)
	gcc -Wall -std=c99 -Werror -pedantic -g $^ -o $@

clean:
	rm -f $(EXE)
