# macOS-bits-stdc-.h

Support for &lt;bits/stdc++.h> in macOS

macOS ships by default with the LLVM/Clang compiler which does not support GNU/GCC extensions such as the bits/stdc++.h header file that every beginner tends to use in their C++ code.

This is a problem even when you use g++ in macOS, as Apple use g++ as a frontend to clang++ for legacy reasons.

# Solution

1. You need to create a directory 'bits' under the folder /usr/local/include.
   This can be done by opening Terminal and running the following commands:
   `mkdir /usr/local/include`
2. You need to c
