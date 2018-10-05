/* CSci4061 F2018 Assignment 1
* login: battu010
* date: 10/05/2018
* Ganzorig Battur, Patrice Martineau, Raymond Holidjaja
* id: battu010, mart3676, holid019 */

We use csel-kh4250-38.cselabs.umn.edu to test our program. 

The most difficult part is the reccursive helper1 function. This function will check all dependencies and made recurrsive call for each of the target dependencies. After checking all dependencies, it will check for the file existence and compare modification time. At the end of this function, it call fork and execvp in child processor and wait while child processor run.

Ganzorig wrote the helper function in the main program, and implemented the main function calls on the program and worked with Patrice on the fork/wait/exec calls within the main.c file, and debugging Phase 2. 

Raymond worked on the error checking as well as tweaking the exec calls in order to fix some of the problems that were occurring with this. He also worked on Phase 1 and laid out the skeleton of the main loops of the Phase 2 program.

Patrice set everything up in Github, formatted the code/comments in the main.c Phase 2 portion and completed documentation. Also worked on fork/wait/exec calls and their implementation within Phase 2, as well as debugging Phase 2.
