install
pacman -S mingw-w64-x86_64-toolchain
pacman -S git make mingw-w64-x86_64-cmake mingw-w64-x86_64-gcc


cmake . -G "MinGW Makefiles"
mingw32-make