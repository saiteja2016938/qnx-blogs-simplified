Welcome back to the series! In the first two posts we managed to:

describe a computer for QEMU to emulate;
describe an image for mkifs to create to run within that computer
which boots QNX, and
displays the message "Hello, your name!"
through the 8250 UART (being emulated by QEMU)
to QEMU's standard output.
Next, in a nod to the book, "The C Programming Language", written by Brian Kernighan & Dennis Ritchie (aka K&R), let's create a simple "Hello, world!" program and get it running on this minimal QNX system.

blog 3 is implemented with this steps 
Create a proper C source file
Build a simple “Hello, World!” QNX application
Integrate it into your QNX image
Run it on QEMU so the OS boots and executes your Hello World program
