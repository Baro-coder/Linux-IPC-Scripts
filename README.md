# Linux-IPC-Scripts

## Repozytorium - co zawiera?
Repozytorium zawiera przykładowe zaawansowane projekty będącymi zestawami programów współdziałających współbieżnie, komunikujących się ze sobą synchronicznie.
Projekty napisane są w języku C pod system operacyjny LINUX.

### Mechanizmy komunikacji:
- łącza nienazwane (pipe)
- łącza nazwane (FIFO)
- kolejki komunikatów (Message Queue)
- pamięć dzielona, semafory (shmem)
- sygnały (signal)

## Repozytorium - dla kogo?
Skrypty skierowane są dla ludzi, którzy już rozpoczęli przygodę z programowaniem
wielowątkowym w języku C i znają mechanizmy IPC w systemie operacyjnym LINUX.
Dane repozytorium realizuje założone zagadnienie w sposób zróżnicowany łącząc
w ramach jednego projektu kilka mechanizmów IPC, a także podstawowe wykorzystanie
języka skryptowego *Bash* w celu ułatwienia pracy z danym projektem.

## Projekty:
1. [C-project - pipe, shared memory, signals](https://github.com/Baro-coder/C-project_pipe-shmem)
2. [C-project - Message queue, signals](https://github.com/Baro-coder/C-project_queue)
3. [C-project - pipe, file, semaphore, signals](https://github.com/Baro-coder/C-project_pipe-file)
