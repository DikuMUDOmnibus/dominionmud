# Generated automatically from Makefile.in by configure.
# CircleMUD 3.0 Makefile.in - Makefile template used by 'configure'
# Modified for use by The Dominion

# C compiler to use
CC = gcc

# Any special flags you want to pass to the compiler
MYFLAGS = -Wall

# flags for profiling (see hacker.doc for more information)
PROFILE = 

# libraries
LIBS = 

##############################################################################
# Do Not Modify Anything Below This Line (unless you know what you're doing) #
##############################################################################

CFLAGS = -g -O2 $(MYFLAGS) $(PROFILE)

OBJFILES = comm.o act_comm.o act_info.o act_item.o act_move.o \
	act_off.o act_othr.o act_socl.o act_wizd.o alias.o \
	ban.o boards.o config.o constant.o creation.o db.o \
	fight.o guild.o graph.o handler.o house.o interpre.o \
	limits.o magic.o mail.o mobact.o mobcmd.o mobprog.o \
	modify.o objsave.o olc.o race.o random.o religion.o save.o \
	shop.o spec_ass.o spec_pro.o spell_pa.o spells.o utils.o \
	weather.o

UTILS = autowiz listrent purgeplay showplay sign split

default: 
	$(MAKE) ../bin/dominion

utils:
	$(MAKE) ../bin/autowiz
	$(MAKE) ../bin/listrent
	$(MAKE) ../bin/purgeplay
	$(MAKE) ../bin/showplay
	$(MAKE) ../bin/sign
	$(MAKE) ../bin/split

all: 
	$(MAKE) ../bin/dominion
	$(MAKE) utils

dominion:
	$(MAKE) ../bin/dominion
autowiz:
	$(MAKE) ../bin/autowiz
listrent:
	$(MAKE) ../bin/listrent
purgeplay:
	$(MAKE) ../bin/purgeplay
showplay:
	$(MAKE) ../bin/showplay
sign:
	$(MAKE) ../bin/sign
split:
	$(MAKE) ../bin/split


../bin/autowiz: util/autowiz.c conf.h sysdep.h structs.h utils.h db.h
	$(CC) $(CFLAGS) -o ../bin/autowiz util/autowiz.c
../bin/listrent: util/listrent.c conf.h sysdep.h structs.h
	$(CC) $(CFLAGS) -o ../bin/listrent util/listrent.c
../bin/mudpasswd: util/mudpasswd.c conf.h sysdep.h structs.h utils.h
	$(CC) $(CFLAGS) -o ../bin/mudpasswd util/mudpasswd.c $(LIBS)
../bin/purgeplay: util/purgeplay.c conf.h sysdep.h structs.h utils.h
	$(CC) $(CFLAGS) -o ../bin/purgeplay util/purgeplay.c
../bin/showplay: util/showplay.c conf.h sysdep.h structs.h
	$(CC) $(CFLAGS) -o ../bin/showplay util/showplay.c
../bin/sign: util/sign.c conf.h sysdep.h
	$(CC) $(CFLAGS) -o ../bin/sign util/sign.c $(LIBS)
../bin/split: util/split.c
	$(CC) $(CFLAGS) -o ../bin/split util/split.c

../bin/dominion : $(OBJFILES)
	$(CC) -o ../bin/dominion $(PROFILE) $(OBJFILES) $(LIBS)
clean:
	rm -f *.o *~ util/*~ ../bin/dominion $(patsubst %,../bin/%,$(UTILS));

realclean:	clean
	@echo "WARNING!! THIS TARGET IS REMOVING YOUR PLAYER FILE AND PLAYER MAIL FILE!!"
	rm -f ../config.log ../config.status ../config.cache ../lib/etc/players ../lib/etc/plrmail ../lib/etc/mudtime ;

# Dependencies for the object files (automagically generated with
# gcc -MM)

act_comm.o: act_comm.c conf.h sysdep.h protos.h
	$(CC) -c $(CFLAGS) act_comm.c
act_info.o: act_info.c conf.h sysdep.h protos.h
	$(CC) -c $(CFLAGS) act_info.c
act_item.o: act_item.c conf.h sysdep.h protos.h
	$(CC) -c $(CFLAGS) act_item.c
act_move.o: act_move.c conf.h sysdep.h protos.h
	$(CC) -c $(CFLAGS) act_move.c
act_off.o: act_off.c conf.h sysdep.h protos.h
	$(CC) -c $(CFLAGS) act_off.c
act_othr.o: act_othr.c conf.h sysdep.h protos.h
	$(CC) -c $(CFLAGS) act_othr.c
act_socl.o: act_socl.c conf.h sysdep.h protos.h
	$(CC) -c $(CFLAGS) act_socl.c
act_wizd.o: act_wizd.c conf.h sysdep.h protos.h
	$(CC) -c $(CFLAGS) act_wizd.c
ban.o: ban.c conf.h sysdep.h protos.h
	$(CC) -c $(CFLAGS) ban.c
boards.o: boards.c conf.h sysdep.h protos.h
	$(CC) -c $(CFLAGS) boards.c
castle.o: castle.c conf.h sysdep.h protos.h
	$(CC) -c $(CFLAGS) castle.c
comm.o: comm.c conf.h sysdep.h protos.h
	$(CC) -c $(CFLAGS) comm.c
config.o: config.c conf.h sysdep.h structs.h
	$(CC) -c $(CFLAGS) config.c
constant.o: constant.c conf.h sysdep.h structs.h
	$(CC) -c $(CFLAGS) constant.c
db.o: db.c conf.h sysdep.h protos.h
	$(CC) -c $(CFLAGS) db.c
fight.o: fight.c conf.h sysdep.h protos.h
	$(CC) -c $(CFLAGS) fight.c
graph.o: graph.c conf.h sysdep.h protos.h
	$(CC) -c $(CFLAGS) graph.c
guild.o: guild.c conf.h sysdep.h protos.h
	$(CC) -c $(CFLAGS) guild.c
handler.o: handler.c conf.h sysdep.h protos.h
	$(CC) -c $(CFLAGS) handler.c
house.o: house.c conf.h sysdep.h protos.h
	$(CC) -c $(CFLAGS) house.c
interpre.o: interpre.c conf.h sysdep.h protos.h
	$(CC) -c $(CFLAGS) interpre.c
limits.o: limits.c conf.h sysdep.h protos.h
	$(CC) -c $(CFLAGS) limits.c
magic.o: magic.c conf.h sysdep.h protos.h
	$(CC) -c $(CFLAGS) magic.c
mail.o: mail.c conf.h sysdep.h protos.h
	$(CC) -c $(CFLAGS) mail.c
mobact.o: mobact.c conf.h sysdep.h protos.h
	$(CC) -c $(CFLAGS) mobact.c
modify.o: modify.c conf.h sysdep.h protos.h
	$(CC) -c $(CFLAGS) modify.c
objsave.o: objsave.c conf.h sysdep.h protos.h
	$(CC) -c $(CFLAGS) objsave.c
olc.o: olc.c conf.h sysdep.h protos.h
	$(CC) -c $(CFLAGS) olc.c
random.o: random.c
	$(CC) -c $(CFLAGS) random.c
race.o: race.c conf.h sysdep.h protos.h
	$(CC) -c $(CFLAGS) race.c
religion.o: religion.c conf.h sysdep.h protos.h
	$(CC) -c $(CFLAGS) religion.c
save.o: save.c conf.h sysdep.h protos.h
	$(CC) -c $(CFLAGS) save.c
shop.o: shop.c conf.h sysdep.h protos.h
	$(CC) -c $(CFLAGS) shop.c
spec_ass.o: spec_ass.c conf.h sysdep.h protos.h
	$(CC) -c $(CFLAGS) spec_ass.c
spec_pro.o: spec_pro.c conf.h sysdep.h protos.h
	$(CC) -c $(CFLAGS) spec_pro.c
spell_pa.o: spell_pa.c conf.h sysdep.h protos.h
	$(CC) -c $(CFLAGS) spell_pa.c
spells.o: spells.c conf.h sysdep.h protos.h
	$(CC) -c $(CFLAGS) spells.c
utils.o: utils.c conf.h sysdep.h protos.h
	$(CC) -c $(CFLAGS) utils.c
weather.o: weather.c conf.h sysdep.h protos.h
	$(CC) -c $(CFLAGS) weather.c
mobcmd.o: mobcmd.c conf.h sysdep.h protos.h
	$(CC) -c $(CFLAGS) mobcmd.c
mobprog.o: mobprog.c conf.h sysdep.h protos.h
	$(CC) -c $(CFLAGS) mobprog.c
alias.o: alias.c conf.h sysdep.h protos.h
	$(CC) -c $(CFLAGS) alias.c
creation.o: creation.c conf.h sysdep.h protos.h
	$(CC) -c $(CFLAGS) creation.c
