# FLOSS test: test-decode-split-stackstrings

Purpose: Demonstrate extraction of different stackstrings split across basic blocks.
Decoding algorithm: stackstrings
Input buffer location: n/a
Output buffer location: stack

Decoded strings:
hello world
hello moon

Source files:
test-decode-split-stackstrings.c

Build instructions (Windows):
cl.exe test-decode-split-stackstrings.c /Fetest-decode-split-stackstrings.exe

Build instructions (Linux):
clang test-decode-split-stackstrings.c -o test-decode-split-stackstrings

Build instructions (Cross compile for Windows on Linux):
i686-w64-mingw32-clang++ test-decode-split-stackstrings.c -o test-decode-split-stackstrings.exe