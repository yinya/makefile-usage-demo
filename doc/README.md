### compile and link.
gcc -o hellomake hellomake.c hellofunc.c -I.

## disadvantage
#First, if you lose the compile command or switch computers you have to retype it from scratch, which is inefficient at best. Second, if you are only making changes to one .c file, recompiling all of them every time is also time-consuming and inefficient. So, it's time to see what we can do with a makefile.
