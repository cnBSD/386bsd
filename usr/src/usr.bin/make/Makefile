#	@(#)Makefile	5.2 (Berkeley) 12/28/90

PROG=	make
LDONLY=ldonly
LIBCRT0=/usr/lib/hcrt0.o
CFLAGS+=-I${.CURDIR}
SRCS=	arch.c buf.c compat.c cond.c dir.c hash.c job.c main.c \
	make.c parse.c str.c suff.c targ.c var.c
SRCS+=	lstAppend.c lstAtEnd.c lstAtFront.c lstClose.c lstConcat.c \
	lstDatum.c lstDeQueue.c lstDestroy.c lstDupl.c lstEnQueue.c \
	lstFind.c lstFindFrom.c lstFirst.c lstForEach.c lstForEachFrom.c \
	lstInit.c lstInsert.c lstIsAtEnd.c lstIsEmpty.c lstLast.c \
	lstMember.c lstNext.c lstOpen.c lstRemove.c lstReplace.c lstSucc.c
.PATH:	${.CURDIR}/lst.lib

.include <bsd.prog.mk>
