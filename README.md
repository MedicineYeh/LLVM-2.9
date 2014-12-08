Low Level Virtual Machine (LLVM)
================================

This directory and its subdirectories contain source code for the Low Level
Virtual Machine, a toolkit for the construction of highly optimized compilers,
optimizers, and runtime environments.

LLVM is open source software. You may freely distribute it under the terms of
the license agreement found in LICENSE.txt.

Please see the HTML documentation provided in docs/index.html for further
assistance with LLVM.

If you're writing a package for LLVM, see docs/Packaging.html for our
suggestions.

# How To Build
1. `mkdir build`
2. `cd build`
3. `../configure --target-list=arm-softmmu --prefix=$PWD` If you want to install llvm in your system, please take away the --prefix option
4. `make -j5`
5. `make install` (Optional, you may need root permission)

# Where is the binaries and libs
If you follow the steps and install in __$PWD__ directory, the files are all in `build/Release` directory.
