CXX = g++
CXX_FLAGS = -Wall -std=c++11 -Dunix -DHAVE_FFTW -I../sigpack -larmadillo -lfftw3

%: %.cpp
	@echo '+++++++++++++++++++++++++++++++++++++++++++++'
	@echo 'Compiling $<, making target ./$@ ...'
	@echo '+++++++++++++++++++++++++++++++++++++++++++++'
	$(CXX) $< $(CXX_FLAGS) -o $@
	
	 	
	
	
