                                   X86_64-GCC-Linaro-7.2.1
                                       android
                                cross-compile toolchain

RUN ./setup to setup the toolchain for use. Requires tar with xz filter support.

The execlib DIR of this TC has been compressed with tar with xz filter & split due to upload errors by git client.

TC for x86_64 architecture for kernel compilation , compiled from Linaro GCC 7.2.1 source with Graphite, Custom GSR and link time optimizations(lto).

This TC has embedded Newlib C library support with plugin & lto optimiztions along with custom CLoog, PPL & GDB code support.


                            setup export commands in .bashrc

                                 export ARCH=x86_64
                         export CROSS_COMPILE=x86_64-linux-
                            export CCOMPILE=$CROSS_COMPILE
                           and your toolchain path ....
                          
                                   Enjoy Compiling
