CC=g++
CFLAGS=-I/software/opencv-2.4.8/include
LDFLAGS=-L/software/opencv-2.4.8/lib -lopencv_core -lopencv_imgproc -lopencv_objdetect -lopencv_highgui

eye_tracking: eye_tracking.cpp
	$(CC) $(CFLAGS) $(LDFLAGS) $< -o $@

clean:
	rm eye_tracking
