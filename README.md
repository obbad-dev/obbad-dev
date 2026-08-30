## Oualid Obbad

Software engineering student at **42 / 1337 (UM6P) Rabat**, focused on **backend development** with Java and systems programming in C/C++.

I like problems where correctness matters: concurrency, memory management, database design, and containerized infrastructure. Most of what I know comes from building things from scratch — a shell-free raycasting engine, a thread-safe simulation, a layered Java application on PostgreSQL, and a multi-container Docker stack.

**Currently seeking a software engineering internship.**

---

### Technical Skills

**Languages**
`Java` · `C` · `C++` · `Python` · `JavaScript` · `Bash` · `SQL`

**Backend & Data**
`Spring Framework (IoC / DI)` · `Spring JDBC` · `JDBC` · `HikariCP` · `PostgreSQL` · `MariaDB` · `Maven` · `JUnit 5` · `Mockito`

**Systems & Tooling**
`Docker` · `Docker Compose` · `NGINX` · `Linux` · `Git & GitHub` · `Make` · `POSIX threads` · `Networking (TCP/IP, TLS)`

---

### Featured Projects

#### [inception-42](https://github.com/obbad-dev/inception-42) — Containerized web infrastructure
A complete multi-service infrastructure built from scratch with Docker, with every service in its own container built from a custom Dockerfile.

- **Stack:** Docker, Docker Compose, NGINX, MariaDB, Redis, WordPress (PHP-FPM), Adminer, dnsmasq, Bash, Make
- **Demonstrates:** service isolation on a dedicated bridge network, NGINX reverse proxy as the sole entrypoint with TLSv1.2/1.3, Docker secrets for credential handling, persistent volumes, and reproducible one-command deployment

#### [pool_java_part2](https://github.com/obbad-dev/pool_java_part2) — Java backend engineering
Four progressive modules covering the layers of a real backend application, built with Maven.

- **Stack:** Java 17+, Maven, PostgreSQL, JDBC, HikariCP, Spring Framework, JUnit 5, Mockito, HSQLDB
- **Demonstrates:**
  - A layered chat application — normalized PostgreSQL schema (users, chatrooms, messages, join tables with foreign keys), a repository layer over JDBC, connection pooling with HikariCP, and service-level transaction handling
  - Unit and integration testing with JUnit 5 and Mockito against an embedded database
  - A **custom ORM** built with Java reflection and custom annotations (`@OrmEntity`, `@OrmColumn`) that maps objects to SQL at runtime
  - Dependency injection and IoC with the Spring container

#### [cub3d](https://github.com/obbad-dev/cub3d_mandatory) — Raycasting 3D engine in C
A Wolfenstein-style renderer that turns a 2D tile map into a navigable 3D view.

- **Stack:** C, MiniLibX, Make
- **Demonstrates:** DDA raycasting with horizontal/vertical intersection selection, texture mapping with per-direction wall textures, a real-time render loop at 1920×1080, custom file parsing and validation, and manual memory management across a modular codebase

#### [philosophers](https://github.com/obbad-dev/philosophers_42) — Concurrency simulation in C
The Dining Philosophers problem solved with real threads and precise timing constraints.

- **Stack:** C, POSIX threads, mutexes
- **Demonstrates:** deadlock avoidance through parity-ordered resource acquisition, race-condition-free shared state, a monitoring thread detecting starvation at millisecond resolution, and clean shutdown of all threads

#### [chat_bot_ISS](https://github.com/obbad-dev/chat_bot_ISS) — AI-powered learning assistant
An interactive educational chatbot delivering lessons, quizzes, and scored feedback.

- **Stack:** Python, Google Gemini API, Gradio
- **Demonstrates:** LLM integration with stateful conversation sessions, application state management across a lesson/quiz flow, answer validation with generated explanations, and UI composition

---

### Also in this profile

- **C++ (98)** — [CPP00–CPP09](https://github.com/obbad-dev?tab=repositories&q=CPP): classes, inheritance, polymorphism, operator overloading, templates, STL containers and iterators
- **C fundamentals** — [libft](https://github.com/obbad-dev/libft) (standard library reimplementation), [ft_printf](https://github.com/obbad-dev/ft_printf) (variadic formatting), [push_swap](https://github.com/obbad-dev/pushSwap) (constrained sorting), [minitalk](https://github.com/obbad-dev/minitalk) (UNIX signal IPC), [so_long](https://github.com/obbad-dev/so_long) (2D game)
- **Java fundamentals** — [pool_java](https://github.com/obbad-dev/pool_java): OOP, collections, exceptions, I/O and streams, multithreading, JAR packaging, JDBC
- **Databases & scripting** — [Celestial_Bodies_Database](https://github.com/obbad-dev/Celestial_Bodies_Database) (PostgreSQL schema design), [database workshops](https://github.com/obbad-dev/worshop_of_data_base) and [Bash scripting](https://github.com/obbad-dev/basic_bash_scripting)

---

### Currently

- Deepening **Spring** — moving from the core container toward web-layer and data-access work
- Strengthening **PostgreSQL** — query design, indexing, and transaction behaviour
- Continuing the **42 cursus**, alongside applying for a software engineering internship

---

### Contact

[![Email](https://img.shields.io/badge/Email-oualidobbad@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:oualidobbad@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Oualid%20Obbad-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/oualid-obbad/)
[![42](https://img.shields.io/badge/42%20intra-oobbad-000000?style=flat-square&logo=42&logoColor=white)](https://profile.intra.42.fr/users/oobbad)

Open to internship opportunities in backend, systems, or software engineering.
