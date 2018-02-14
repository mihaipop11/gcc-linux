# gcc-linux
gcc bug

how to reproduce:

works:
  g++ "-D INCLUDE_FILE=\"${PWD}/include/include.hpp\"" main.cpp

doesn't work:
  g++ "-D INCLUDE_FILE=<${PWD}/include/include.hpp>" main.cpp
