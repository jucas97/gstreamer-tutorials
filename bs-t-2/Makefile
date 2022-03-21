CC = gcc
CFLAGS = `pkg-config --cflags --libs gstreamer-1.0`

basic-2: basic-tutorial-2.c
	${CC} basic-tutorial-2.c -o basic-2 ${CFLAGS}

clean:
	rm -f basic-2*