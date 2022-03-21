CC = gcc
CFLAGS = `pkg-config --cflags --libs gstreamer-1.0`

basic-3: basic-tutorial-3.c
	${CC} basic-tutorial-3.c -o basic-3 ${CFLAGS}

basic-3-exer: basic-tutorial-3-exer.c
	${CC} basic-tutorial-3-exer.c -o basic-3-exer ${CFLAGS}

clean:
	rm -f basic-3*
