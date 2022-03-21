CC = gcc
CFLAGS = `pkg-config --cflags --libs gstreamer-1.0`

basic-1: basic-tutorial-1.c
	${CC} basic-tutorial-1.c -o basic-1 ${CFLAGS}

clean:
	rm -f basic-1*