bin_PROGRAMS=tcpcopy

tcpcopy_SOURCES=\
                tcpcopy.h\
                address.c address.h\
                send.c send.h\
                manager.c manager.h\
                session.c session.h\
                main.c
tcpcopy_LDADD=\
               ../core/libcore.a\
               ../util/libutil.a\
               ../mysql/libmysql.a\
               ../event/libevent.a\
               ../communication/libmsg.a\
               -lm
