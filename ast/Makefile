#
# Important! Dependencies are done automatically by 'make dep', which also
# removes any old dependencies. Do not modify it...
# 2021, d3phys
#

OBJS = parse.o dump_tree.o tree.o 

ast.o: $(OBJS) subdirs
	$(LD) -r -o $@ $(OBJS)

include $(TOPDIR)/Rules.makefile

### Dependencies ###
dump_tree.o: dump_tree.cpp \
 /home/d3phys/Code/assert-lang-old/assert-lang/include/logs.h \
 /home/d3phys/Code/assert-lang-old/assert-lang/include/ast/tree.h \
 /home/d3phys/Code/assert-lang-old/assert-lang/include/array.h
parse.o: parse.cpp \
 /home/d3phys/Code/assert-lang-old/assert-lang/include/iommap.h \
 /home/d3phys/Code/assert-lang-old/assert-lang/include/logs.h \
 /home/d3phys/Code/assert-lang-old/assert-lang/include/array.h \
 /home/d3phys/Code/assert-lang-old/assert-lang/include/ast/tree.h \
 /home/d3phys/Code/assert-lang-old/assert-lang/include/ast/keyword.h \
 /home/d3phys/Code/assert-lang-old/assert-lang/include/ast/../../AST \
 ../AST
tree.o: tree.cpp \
 /home/d3phys/Code/assert-lang-old/assert-lang/include/logs.h \
 /home/d3phys/Code/assert-lang-old/assert-lang/include/stack.h \
 /home/d3phys/Code/assert-lang-old/assert-lang/include/ast/tree.h \
 /home/d3phys/Code/assert-lang-old/assert-lang/include/array.h \
 /home/d3phys/Code/assert-lang-old/assert-lang/include/ast/keyword.h \
 /home/d3phys/Code/assert-lang-old/assert-lang/include/ast/../../AST \
 ../AST
