#
# Important! Dependencies are done automatically by 'make dep', which also
# removes any old dependencies. Do not modify it...
# 2021, d3phys
#

OBJS = lexer.o ident.o recursive_descent.o

frontend.o: $(OBJS) subdirs
	$(LD) -r -o $@ $(OBJS)

include $(TOPDIR)/Rules.makefile

### Dependencies ###
ident.o: ident.cpp \
 /home/d3phys/Code/assert-lang-old/assert-lang/include/frontend/keyword.h \
 /home/d3phys/Code/assert-lang-old/assert-lang/include/../KEYWORDS \
 ../KEYWORDS
lexer.o: lexer.cpp \
 /home/d3phys/Code/assert-lang-old/assert-lang/include/logs.h \
 /home/d3phys/Code/assert-lang-old/assert-lang/include/list.h \
 /home/d3phys/Code/assert-lang-old/assert-lang/include/array.h \
 /home/d3phys/Code/assert-lang-old/assert-lang/include/ast/tree.h \
 /home/d3phys/Code/assert-lang-old/assert-lang/include/frontend/token.h \
 /home/d3phys/Code/assert-lang-old/assert-lang/include/frontend/keyword.h \
 /home/d3phys/Code/assert-lang-old/assert-lang/include/../KEYWORDS \
 ../KEYWORDS
main.o: main.cpp \
 /home/d3phys/Code/assert-lang-old/assert-lang/include/logs.h \
 /home/d3phys/Code/assert-lang-old/assert-lang/include/array.h \
 /home/d3phys/Code/assert-lang-old/assert-lang/include/iommap.h \
 /home/d3phys/Code/assert-lang-old/assert-lang/include/ast/tree.h \
 /home/d3phys/Code/assert-lang-old/assert-lang/include/frontend/token.h \
 /home/d3phys/Code/assert-lang-old/assert-lang/include/frontend/compile.h
recursive_descent.o: recursive_descent.cpp \
 /home/d3phys/Code/assert-lang-old/assert-lang/include/logs.h \
 /home/d3phys/Code/assert-lang-old/assert-lang/include/ast/tree.h \
 /home/d3phys/Code/assert-lang-old/assert-lang/include/array.h \
 /home/d3phys/Code/assert-lang-old/assert-lang/include/ast/keyword.h \
 /home/d3phys/Code/assert-lang-old/assert-lang/include/ast/../../AST \
 /home/d3phys/Code/assert-lang-old/assert-lang/include/frontend/keyword.h \
 /home/d3phys/Code/assert-lang-old/assert-lang/include/../KEYWORDS \
 /home/d3phys/Code/assert-lang-old/assert-lang/include/frontend/token.h
