## Operating Systems Course - DIEF UNIMORE ##
## Implementing "head" command in xv6, project by Gasparini Nicolo' ##

The project consist in the implementation of the "head" command in a proper way, so that it may work on the XV6 operating system.
The command is written using the C language, with the system calls and function available with the basic version of XV6.
To understand how this command works it's possible to use the option --help
The possible arguments are:
  -n NUM  to operate with number of lines
  -c NUM  to operate with number of bytes
  -q      quiet mode
  -v      verbose mode

2 text files have been added in order to test the function, when removed, the MAKEFILE must be modified too.

NOT IMPLEMENTED:
  multiplier suffix, as in standard unix function
  -NUM option, since it works with -n NUM
  -z option for zero terminated lines
