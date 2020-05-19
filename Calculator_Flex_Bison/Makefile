default:
	bison -d r2.y
	flex r2.l 
	gcc lex.yy.c r2.tab.c -o r2

complie:
	bison r2.y 
	flex r2.l 
	gcc lex.yy.c y.tab.c -o r2
	make clean

clean:
	rm -f r2.tab.c r2.tab.h y.tab.h y.tab.c lex.yy.c
