all: build

FILES = code8080.c while.c sym.c stmt.c primary.c preproc.c main.c lex.c io.c gen.c function.c expr.c error.c data.c 

build:
	cd .. && cl /Fewindows/cc8080.exe $(FILES)

clean:
	del *.obj *.exe
