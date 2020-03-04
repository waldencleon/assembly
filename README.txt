If you are developing on x64 CPU, ensure that you detail in your make file that the linker should be expecting x86 format. 

Example:


Ld -o <executablename> sandbox.o -melf_i386
