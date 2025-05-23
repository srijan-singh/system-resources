# System Resources


✅ Week 1–2: Memory & Pointers
malloc, calloc, free, realloc

memcpy, memset

- [ ] Build: Your own malloc() (use sbrk())

Tools: valgrind, gdb

🛠 Project: Memory pool allocator

✅ Week 3: File I/O and System Calls
open, read, write, close

fopen vs open (high vs low level)

- [ ] Build: Copy file utility, logger, file watcher

Tool: strace to inspect file calls

✅ Week 4: Processes and Exec
fork(), exec(), wait(), kill()

- [ ] Build: Minimal shell (sh >)

Learn: Parent-child processes, signals

Tool: pstree, kill, ps

✅ Week 5: Multithreading
pthread_create, pthread_join, mutex, cond

Race conditions, deadlocks

- [ ] Build: Thread pool, downloader

Tool: htop, valgrind --tool=helgrind

✅ Week 6–7: Networking (Sockets)
socket, bind, connect, accept, send, recv

TCP vs UDP

- [ ] Build: Echo server, then simple HTTP server
