These are the LLVM tasks for Lesson 7 in Cornell's [CS6120](https://www.cs.cornell.edu/courses/cs6120/2022sp/) class.

Pong implementation is from github user flightcrank, and is available [here](https://github.com/flightcrank/pong).

This program is intended to add instrumentation to pong to log the time spent in an SDL function, but calling some logging functions before and after every call to a function who's name starts with `SDL_`.
