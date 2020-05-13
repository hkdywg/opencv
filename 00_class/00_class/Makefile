CFLAGS =-g -Wall -std=c++11
INCLUDE = -I /usr/local/include/opencv4
LDFLAGS:= -L/usr/local/lib -lopencv_core -lopencv_highgui -lopencv_imgproc -lpthread -lopencv_videoio -lopencv_photo -lopencv_imgcodecs
OBJS = main.cpp
CXX = g++
all: demo
demo: $(OBJS)
	$(CXX) $(CFLAGS) $(OBJS) $(INCLUDE) $(LDFLAGS) -o $@ 
clean:
	rm -f demo
