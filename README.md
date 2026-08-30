## Oualid Obbad

Software engineering student at **42 / 1337 (UM6P) Rabat**, specializing in **backend development**.

I build systems from the ground up: an HTTP/1.1 web server on a non-blocking event loop, a POSIX shell, a layered Java application over PostgreSQL, and a multi-container Docker infrastructure. I work most confidently in **C, C++, and Java**, and I'm currently focused on the **Java/Spring** backend ecosystem.

**Open to a software engineering internship.**

---

### Technical Skills

| | |
|---|---|
| **Core languages** | C · C++ (98) · Java |
| **Backend** | Spring Framework (IoC / DI) · Spring JDBC · JDBC · HikariCP · Maven · JUnit 5 · Mockito · HTTP/1.1 · CGI · REST fundamentals |
| **Databases** | PostgreSQL · MariaDB · SQL schema design |
| **Systems & tools** | Linux · Docker · Docker Compose · NGINX · Git & GitHub · Make · POSIX threads · Sockets & `epoll` |
| **Secondary** | JavaScript · HTML · CSS · Bash · Python (basics) |

---

### Featured Projects

#### [webserv](https://github.com/obbad-dev/webServ) — HTTP/1.1 web server in C++98
*Team of 2.* An NGINX-inspired web server written from scratch, with no external libraries.

Single-threaded, non-blocking event loop built on `epoll()`. Implements `GET`/`POST`/`DELETE`, a hand-written tokenizer and parser for an NGINX-style configuration file, virtual hosting with `server_name` matching, per-route rules, CGI execution, multipart file uploads, directory autoindex, configurable error pages, redirects, and request body size limits.

`C++98` · `Sockets` · `epoll` · `HTTP/1.1` · `CGI` · `Make`

**Demonstrates:** network and socket programming, I/O multiplexing, protocol implementation from an RFC, parser design, and object-oriented architecture across a large C++ codebase.

#### [pool_java_part2](https://github.com/obbad-dev/pool_java_part2) — Java backend engineering
Four Maven modules covering the layers of a real backend application.

A chat application built on a normalized PostgreSQL schema (users, chatrooms, messages, join tables with foreign keys) with a repository layer over JDBC and connection pooling via HikariCP. Includes unit and integration tests with JUnit 5 and Mockito against an embedded database, a **custom ORM** driven by Java reflection and custom annotations (`@OrmEntity`, `@OrmColumn`), and dependency injection through the Spring container.

`Java 17+` · `Maven` · `PostgreSQL` · `JDBC` · `HikariCP` · `Spring Framework` · `JUnit 5` · `Mockito`

**Demonstrates:** layered backend architecture, relational modelling, data-access design, dependency injection, and testing discipline.

#### [minishell](https://github.com/obbad-dev/minishell) — POSIX shell in C
*Team of 2.* A Bash-like shell built from scratch, with no parsing libraries.

Full pipeline: lexer → variable expansion → parser → execution. Supports pipes, input/output/append redirection, heredocs, single and double quoting rules, `$VAR` and `$?` expansion, ambiguous-redirect detection, the seven required builtins (`echo`, `cd`, `pwd`, `export`, `unset`, `env`, `exit`), Bash-accurate signal behaviour, and a custom tracking allocator for leak-free cleanup.

`C` · `Processes & fork/execve` · `Pipes` · `File descriptors` · `Signals` · `GNU Readline`

**Demonstrates:** UNIX process and file-descriptor management, tokenizer and recursive-descent parser design, signal handling, and disciplined memory management.

#### [inception](https://github.com/obbad-dev/inception-42) — Containerized infrastructure
A multi-service stack where every service runs in its own container from a hand-written Dockerfile.

NGINX reverse proxy as the sole entrypoint with TLSv1.2/1.3, WordPress on PHP-FPM, MariaDB, Redis cache, Adminer, an FTP server, and a local DNS resolver — all on an isolated bridge network, with credentials handled through Docker secrets, persistent volumes, and a single-command Make deployment.

`Docker` · `Docker Compose` · `NGINX` · `MariaDB` · `Redis` · `Linux` · `Bash` · `Make`

**Demonstrates:** container orchestration, service isolation, reverse proxying and TLS, secret handling, and reproducible infrastructure.

#### [cub3D](https://github.com/obbad-dev/cub3d_mandatory) — Raycasting 3D engine in C
A Wolfenstein-style renderer that turns a 2D tile map into a navigable 3D view.

DDA raycasting with horizontal/vertical intersection selection, per-direction wall texture mapping, a real-time render loop at 1920×1080, a minimap, and a custom `.cub` scene-file parser with full validation.

`C` · `MiniLibX` · `Make`

**Demonstrates:** applied geometry, real-time rendering, modular C design, and manual memory management.

#### [philosophers](https://github.com/obbad-dev/philosophers_42) — Concurrency in C
The Dining Philosophers problem under strict timing constraints.

Deadlock avoidance via parity-ordered resource acquisition, race-condition-free shared state, a dedicated monitoring thread detecting starvation at millisecond resolution, and clean shutdown of every thread.

`C` · `POSIX threads` · `Mutexes`

**Demonstrates:** multithreading, synchronization primitives, deadlock and race-condition reasoning.

---

### Also on this profile

- **C++98 / OOP** — [CPP00–CPP09](https://github.com/obbad-dev?tab=repositories&q=CPP): inheritance, polymorphism, operator overloading, exceptions, templates, STL containers and iterators
- **C fundamentals** — [libft](https://github.com/obbad-dev/libft) · [ft_printf](https://github.com/obbad-dev/ft_printf) · [push_swap](https://github.com/obbad-dev/pushSwap) · [minitalk](https://github.com/obbad-dev/minitalk) · [so_long](https://github.com/obbad-dev/so_long)
- **Java fundamentals** — [pool_java](https://github.com/obbad-dev/pool_java): OOP, collections, exceptions, I/O and streams, multithreading, JAR packaging, JDBC
- **Databases & scripting** — [Celestial_Bodies_Database](https://github.com/obbad-dev/Celestial_Bodies_Database) · [database workshops](https://github.com/obbad-dev/worshop_of_data_base) · [Bash scripting](https://github.com/obbad-dev/basic_bash_scripting)
- **Web basics** — [html-css](https://github.com/obbad-dev/html-css): responsive layouts with Flexbox and Grid

---

### Currently

Learning **Spring Boot** — building on the Spring core container and Spring JDBC work above, toward REST APIs and persistence. Alongside it, deepening PostgreSQL (query design, indexing, transactions) and continuing the 42 cursus.

---

### Contact

[![Email](https://img.shields.io/badge/Email-oualidobbad@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:oualidobbad@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Oualid%20Obbad-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/oualid-obbad/)
[![42](https://img.shields.io/badge/42%20intra-oobbad-000000?style=flat-square&logo=42&logoColor=white)](https://profile.intra.42.fr/users/oobbad)
