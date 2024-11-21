# CPP_Practice
This branch mainly focus on coding practice


# C++ Threads:
 - C++ Threads are introduced in c++11. Prior to this the threads were created using POSIX pthread 3rd party library, which makes it non-portable.
 - C++ Threads actually can be created using the underlying OS supported thread implementations, for e.g. in Windows OS it uses createThread(), in Unix-like systems it uses POSIX's pthread_create().

 - The difference b/w POSIX and C++ Threads are follows:
 - 
| C++ Threads   | POSIX Threads |
|---|---|
| The C++ std thread library is part of the C++ standard library and provides a C++ interface              | The POSIX threads library is a separate library that provides a C interface. |
| C++ std threads are typically implemented using a combination of user-level and kernel-level threads     | POSIX threads are typically implemented using kernel-level threads. |
| C++ std threads are part of the C++ standard library, which makes them more portable than POSIX threads  | POSIX threads, which are a separate library and may not be available on all platforms   |
