# gRPC C++ Hello World with CMake

This is just [gRPCs](https://github.com/grpc/grpc) C++ Hello World sample 
([see here](https://github.com/grpc/grpc/tree/release-0_11/examples/cpp)), but
instead of using plain makefiles, I'm using CMake. You need to have gRPC
installed to make this run.

## Compile

1. `git clone https://github.com/jan-alexander/grpc-cpp-helloworld-cmake
   ~/grpc-cpp-helloworld-cmake`
2. `cd ~/grpc-cpp-helloworld-cmake`
3. `mkdir build && cd build`
4. `cmake ..`
5. `make`
