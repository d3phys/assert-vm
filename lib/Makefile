#
# Important! Dependencies are done automatically by 'make dep', which also
# removes any old dependencies. Do not modify it...
# 2021, d3phys
#

OBJS  = logs.o iommap.o stack.o list.o array.o

lib.o: $(OBJS) subdirs
	$(LD) -r -o $@ $(OBJS)

include $(TOPDIR)/Rules.makefile

### Dependencies ###
array.o: array.cpp \
 /home/d3phys/Code/assert-lang-old/assert-lang/include/array.h \
 /home/d3phys/Code/assert-lang-old/assert-lang/include/logs.h
iommap.o: iommap.cpp \
 /home/d3phys/Code/assert-lang-old/assert-lang/include/iommap.h
list.o: list.cpp \
 /home/d3phys/Code/assert-lang-old/assert-lang/include/logs.h \
 /home/d3phys/Code/assert-lang-old/assert-lang/include/list.h
listdev.o: listdev.cpp \
 /home/d3phys/Code/assert-lang-old/assert-lang/include/list.h
logs.o: logs.cpp \
 /home/d3phys/Code/assert-lang-old/assert-lang/include/logs.h
stack.o: stack.cpp \
 /home/d3phys/Code/assert-lang-old/assert-lang/include/logs.h \
 /home/d3phys/Code/assert-lang-old/assert-lang/include/stack.h
