
SRCS = ../src/CRtspSession.cpp ../src/CStreamer.cpp ../src/JPEGSamples.cpp ../src/SimStreamer.cpp

run: *.cpp ../src/*
	g++ -o testserver -I ../src -I . *.cpp $(SRCS) -std=c++17
	./testserver
