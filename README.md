# gcc-linux (bug)

## works
```
git clone https://github.com/mihaipop11/gcc-linux.git gcc-dir
g++ "-D INCLUDE_FILE=\"${PWD}/include/include.hpp\"" main.cpp
g++ "-D INCLUDE_FILE=<${PWD}/include/include.hpp>" main.cpp
```
## this works too
```
git clone https://github.com/mihaipop11/gcc-linux.git gcc-linux
g++ "-D INCLUDE_FILE=\"${PWD}/include/include.hpp\"" main.cpp
```

### Issue is here
```
g++ "-D INCLUDE_FILE=<${PWD}/include/include.hpp>" main.cpp
```
