CC=clang++
LIBS=`wx-config --libs`
CFLAGS=`wx-config --cflags`
SOURCE=console.cpp
TARGET=console

all:
	${CC} -o ${TARGET} ${LIBS} ${CFLAGS} ${SOURCE}

clear:
	rm -f ${TARGET}
