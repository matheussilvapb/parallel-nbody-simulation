# parallel-nbody-simulation

This was a task made for the concurrent programming course (INE5410), taken at
UFSC. We received a [sequential version](nbody.c) of a [N-Body
simulation](https://en.wikipedia.org/wiki/N-body_simulation) C program, and the
task was to make a [parallel version](parallel/parallel.c) of this code using
POSIX threads.  You can compile it by running `make`, and run the sequential
and parallel version with:
```
$ ./nbody arg1 arg2 arg3
$ ./parallel arg1 arg2 arg3 arg4
```
Where,
* arg1 = number of particles.
* arg2 = number of iterations.
* arg3 = if not equal to 0, the program will print the final positions of all
  particles.
* arg4 = number of threads to be used in simulation.
