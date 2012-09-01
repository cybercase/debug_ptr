debug_ptr
=========

debug_ptr is a smart pointer designed to help with avoiding memory leaks.

See debug_ptr.h for documentation.
See debug_ptr_test.cpp for some use case examples.

compile with:
g++ -Wall -o test debug_ptr_test.cc -DENABLE_DEBUG_TYPES
