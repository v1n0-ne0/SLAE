# x86 Assembly Language and Shellcoding on Linux - SLAE

Source code, tools and binaries for Pentester Academy *x86 Assembly Language and Shellcoding on Linux* course.

This blog post has been created for completing the requirements of the [SecurityTube Linux Assembly Expert certification](https://www.pentesteracademy.com/course?id=3). 

Compiled on Ubuntu Mate 18.04 64-bit.

Student ID: PA-7449 

## Assignment 1: Create Shell_Bind_TCP shellcode

NASM: [bindtcp.nasm](https://github.com/fuzboxz/SLAE/tree/master/assignments/bindtcp/bindtcp.nasm)

Shellcode generator: [bindtcp.py](https://github.com/fuzboxz/SLAE/tree/master/assignments/bindtcp/bindtcp.py)

Shellcode tester: [bindtcp.c](https://github.com/fuzboxz/SLAE/tree/master/assignments/bindtcp/bindtcp.c)

Call graph: [shell.png](https://github.com/fuzboxz/SLAE/tree/master/assignments/bindtcp/shell.png)

Binary: [bindtcp](https://github.com/fuzboxz/SLAE/tree/master/assignments/bindtcp/bindtcp)

## Assignment 2: Reverse Shell TCP shellcode

NASM: [reversetcp.nasm](https://github.com/fuzboxz/SLAE/tree/master/assignments/reversetcp/reversetcp.nasm)

Shellcode generator: [reversetcp.py](https://github.com/fuzboxz/SLAE/tree/master/assignments/reversetcp/reversetcp.py)

Shellcode tester: [reversetcp.c](https://github.com/fuzboxz/SLAE/tree/master/assignments/reversetcp/reversetcp.c)

Call graph: [shell.png](https://github.com/fuzboxz/SLAE/tree/master/assignments/reversetcp/shell.png)

Binary: [reversetcp](https://github.com/fuzboxz/SLAE/tree/master/assignments/reversetcp/reversetcp)

## Assignment 3: Create egghunter demo with configurable second stage

NASM: [egghunter.nasm](https://github.com/fuzboxz/SLAE/tree/master/assignments/egghunter/egghunter.nasm)

Shellcode tester: [egghunter.c](https://github.com/fuzboxz/SLAE/tree/master/assignments/egghunter/egghunter.c)

Call graph: [shell.png](https://github.com/fuzboxz/SLAE/tree/master/assignments/egghunter/shell.png)

Binary: [egghunter](https://github.com/fuzboxz/SLAE/tree/master/assignments/egghunter/egghunter)

## Assignment 4: Create custom encoding with execve stack shellcode

NASM: [decode.nasm](https://github.com/fuzboxz/SLAE/tree/master/assignments/encoder/decode.nasm)

Encoder: [encode.py](https://github.com/fuzboxz/SLAE/tree/master/assignments/encoder/encode.py)

Binary: [decode_shellcode (ELF)](https://github.com/fuzboxz/SLAE/tree/master/assignments/encoder/decode_shellcode)


## Assignment 5: Analyze at least 3 shellcode from msfpayload linux/x86

Notes: [notes.txt](https://github.com/fuzboxz/SLAE/tree/master/assignments/msfvenom/notes.txt)

chmod graph: [chmod.png](https://github.com/fuzboxz/SLAE/tree/master/assignments/msfvenom/chmod.png)

readpasswd graph: [readpasswd.png](https://github.com/fuzboxz/SLAE/tree/master/assignments/msfvenom/readpasswd.png)

revshell graph: [revshell.png](https://github.com/fuzboxz/SLAE/tree/master/assignments/msfvenom/revshell.png)

## Assignment 6: Create polymorphic version for 3 shellcodes from Shell-Storm (not larger than 150%)

Polymorphic shellcode and C source [polymorph](https://github.com/fuzboxz/SLAE/tree/master/assignments/polymorphic) 

## Assignment 7: Create custom crypter for shellcode in any language

Source: [crypter.py](https://github.com/fuzboxz/SLAE/blob/master/assignments/crypter/crypter.py)
