# gcc-linux 

## works
```
git clone https://github.com/mihaipop11/gcc-linux.git test-notlinux
g++ "-D INCLUDE_FILE=\"${PWD}/include/include.hpp\"" main.cpp
g++ "-D INCLUDE_FILE=<${PWD}/include/include.hpp>" main.cpp
```

## this works too
```
git clone https://github.com/mihaipop11/gcc-linux.git test-linux
g++ "-D INCLUDE_FILE=\"${PWD}/include/include.hpp\"" main.cpp
```
## but this...
```
g++ "-D INCLUDE_FILE=<${PWD}/include/include.hpp>" main.cpp
```
