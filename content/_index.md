---
title: The AFL++ fuzzing framework
type: docs
bookToc: false
---

# AFL++ Overview

The AFL++ fuzzing framework includes the following:

+ A fuzzer with many mutators and configurations: afl-fuzz.
+ Different source code instrumentation modules: LLVM mode, afl-as, GCC plugin.
+ Different binary code instrumentation modules: QEMU mode, Unicorn mode, QBDI mode.
+ Utilities for testcase/corpus minimization: afl-tmin, afl-cmin.
+ Helper libraries: libtokencap, libdislocator, libcompcov.

# What is AFL++ 

AFLplusplus is the son of the American Fuzzy Lop fuzzer and was created initially to incorporate all the best features developed in the years for the fuzzers in the AFL family and not merged in AFL cause it is not updated since November 2017.


