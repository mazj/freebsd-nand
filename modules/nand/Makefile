# $FreeBSD$

.PATH: ${.CURDIR}/../../dev/nand

KMOD=	nand
SRCS=	nand.c nandreg.h nandvar.h
WARNS?=	6

CFLAGS+= -DINVARIANTS

.include <bsd.kmod.mk>

