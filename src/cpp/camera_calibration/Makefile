CFLAGS=`pkg-config --cflags opencv`
LIBS=`pkg-config --libs opencv`
camera_calibration : camera_calibration.cpp
	g++ $(CFLAGS) -o $@ $< $(LIBS)
