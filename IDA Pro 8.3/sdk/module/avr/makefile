PROC=avr
CONFIGS=avr.cfg
ifndef NOTEAMS

endif

include ../module.mak

# MAKEDEP dependency list ------------------
$(F)ana$(O)     : $(I)auto.hpp $(I)bitrange.hpp $(I)bytes.hpp               \
                  $(I)config.hpp  $(I)diskio.hpp               \
                  $(I)entry.hpp $(I)fixup.hpp $(I)fpro.h $(I)funcs.hpp      \
                  $(I)ida.hpp $(I)idp.hpp $(I)ieee.h $(I)kernwin.hpp        \
                  $(I)lines.hpp $(I)llong.hpp $(I)loader.hpp   \
                   $(I)nalt.hpp $(I)name.hpp                \
                  $(I)netnode.hpp $(I)offset.hpp $(I)pro.h                  \
                  $(I)problems.hpp $(I)range.hpp $(I)segment.hpp            \
                  $(I)ua.hpp $(I)xref.hpp ../../ldr/elf/elfbase.h           \
                   ../idaidp.hpp ../iohandler.hpp   \
                  ana.cpp avr.hpp ins.hpp
$(F)emu$(O)     : $(I)auto.hpp $(I)bitrange.hpp $(I)bytes.hpp               \
                  $(I)config.hpp  $(I)diskio.hpp               \
                  $(I)entry.hpp $(I)fixup.hpp $(I)fpro.h $(I)funcs.hpp      \
                  $(I)ida.hpp $(I)idp.hpp $(I)ieee.h $(I)kernwin.hpp        \
                  $(I)lines.hpp $(I)llong.hpp $(I)loader.hpp   \
                   $(I)nalt.hpp $(I)name.hpp                \
                  $(I)netnode.hpp $(I)offset.hpp $(I)pro.h                  \
                  $(I)problems.hpp $(I)range.hpp $(I)segment.hpp            \
                  $(I)ua.hpp $(I)xref.hpp ../../ldr/elf/elfbase.h           \
                   ../idaidp.hpp ../iohandler.hpp   \
                  avr.hpp emu.cpp ins.hpp
$(F)ins$(O)     : $(I)auto.hpp $(I)bitrange.hpp $(I)bytes.hpp               \
                  $(I)config.hpp  $(I)diskio.hpp               \
                  $(I)entry.hpp $(I)fixup.hpp $(I)fpro.h $(I)funcs.hpp      \
                  $(I)ida.hpp $(I)idp.hpp $(I)ieee.h $(I)kernwin.hpp        \
                  $(I)lines.hpp $(I)llong.hpp $(I)loader.hpp   \
                   $(I)nalt.hpp $(I)name.hpp                \
                  $(I)netnode.hpp $(I)offset.hpp $(I)pro.h                  \
                  $(I)problems.hpp $(I)range.hpp $(I)segment.hpp            \
                  $(I)ua.hpp $(I)xref.hpp ../../ldr/elf/elfbase.h           \
                   ../idaidp.hpp ../iohandler.hpp   \
                  avr.hpp ins.cpp ins.hpp
$(F)out$(O)     : $(I)auto.hpp $(I)bitrange.hpp $(I)bytes.hpp               \
                  $(I)config.hpp  $(I)diskio.hpp               \
                  $(I)entry.hpp $(I)fixup.hpp $(I)fpro.h $(I)funcs.hpp      \
                  $(I)ida.hpp $(I)idp.hpp $(I)ieee.h $(I)kernwin.hpp        \
                  $(I)lines.hpp $(I)llong.hpp $(I)loader.hpp   \
                   $(I)nalt.hpp $(I)name.hpp                \
                  $(I)netnode.hpp $(I)offset.hpp $(I)pro.h                  \
                  $(I)problems.hpp $(I)range.hpp $(I)segment.hpp            \
                  $(I)ua.hpp $(I)xref.hpp ../../ldr/elf/elfbase.h           \
                   ../idaidp.hpp ../iohandler.hpp   \
                  avr.hpp ins.hpp out.cpp
$(F)reg$(O)     : $(I)auto.hpp $(I)bitrange.hpp $(I)bytes.hpp               \
                  $(I)config.hpp                  \
                  $(I)diskio.hpp $(I)entry.hpp $(I)fixup.hpp $(I)fpro.h     \
                  $(I)funcs.hpp $(I)ida.hpp $(I)idp.hpp $(I)ieee.h          \
                  $(I)kernwin.hpp $(I)lines.hpp $(I)llong.hpp               \
                  $(I)loader.hpp               \
                  $(I)nalt.hpp $(I)name.hpp $(I)netnode.hpp $(I)offset.hpp  \
                  $(I)pro.h $(I)problems.hpp $(I)range.hpp $(I)segment.hpp  \
                  $(I)segregs.hpp $(I)ua.hpp $(I)xref.hpp                   \
                  ../../ldr/elf/elfbase.h           \
                  ../idaidp.hpp ../iohandler.hpp avr.hpp ins.hpp            \
                  notify_codes.hpp reg.cpp
