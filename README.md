# 42 Common Core

Projects from the Common Core at [42 Luxembourg](https://42luxembourg.lu), completed 2024–2026. Everything is written from scratch, with no external libraries unless the subject provides them (MiniLibX). Each folder has its own README with build and usage instructions.

## C

| Project | What it is | Concepts |
|---|---|---|
| [libft](libft/) | My own C standard library, reused across later projects | Memory, strings, linked lists, Makefiles |
| [ft_printf](libftprintf/) | Reimplementation of `printf` as a static library | Variadic functions, formatting |
| [get_next_line](GetNextLine/) | Reads a file one line at a time | Static buffers, file descriptors |
| [push_swap](push_swap/) | Sorts integers with two stacks and a limited set of operations | Algorithms (radix sort), complexity |
| [minitalk](Minitalk/) | Client–server messaging using only UNIX signals | `SIGUSR1`/`SIGUSR2`, signal handling |
| [fract-ol](fractol/) | Interactive fractal viewer (Mandelbrot, Julia, Burning Ship) | Graphics, complex numbers, events |
| [philosophers](Philosophers/) | The dining philosophers problem | POSIX threads, mutexes, deadlocks, data races |

## C++

| Project | What it is | Concepts |
|---|---|---|
| [C++ Modules 00–09](C++/) | Ten modules of exercises in C++98 | OOP, polymorphism, templates, STL, exceptions |

## Larger projects (separate repos)

- [Transcendence](https://github.com/alex-henriques/Transcendence): real-time multiplayer quiz game; I was tech lead and built the Docker and nginx infrastructure
- [Taskmaster](https://github.com/alex-henriques/Taskmaster): process supervisor in Python
- [Inception](https://github.com/alex-henriques/Inception): WordPress, MariaDB and NGINX stack, each in its own container; Docker, Docker Compose, TLS, Docker secrets
