                                   X86_64-GCC-6.1.0 
                                       android
                                cross-compile toolchian

RUN ./setup to setup the toolcahin for use

had to zip a few files cause github was throwing errors due to their size.

toolchain for x86_64 architecture for kernel compilation , compiled from GNU GCC 6.1.0 source with graphite and link time optimizations(lto).


                            setup export commands in .bashrc

                                 export ARCH=x86_64
                            export CCOMPILE=$CROSS_COMPILE
                         export CROSS_COMPILE=x86_64-linux-android-
                           and your toolchain path ....
                          
                                   Enjoy Compiling
