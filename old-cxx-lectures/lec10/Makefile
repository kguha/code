default: build/Makefile
	make -C build

TEST = Int_vector_tests

hard: build/Makefile
	make -C build
	build/$(TEST)

build/Makefile: CMakeLists.txt
	mkdir -p build
	cd build; cmake ..
