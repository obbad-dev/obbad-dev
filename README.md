<!-- ═══════════════════════ HEADER ═══════════════════════ -->

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,45:1f2937,100:F7A41D&height=190&section=header&text=Oualid%20Obbad&fontSize=48&fontColor=ffffff&fontAlignY=34&desc=Backend%20Developer%20%E2%80%A2%20C%20%2F%20C%2B%2B%20%2F%20Java&descSize=17&descAlignY=54&animation=fadeIn" width="100%" alt="Oualid Obbad" />

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=21&duration=2800&pause=900&color=F7A41D&center=true&vCenter=true&width=620&lines=Backend+Development+%E2%80%A2+Java+%26+Spring;Systems+Programming+in+C+%26+C%2B%2B98;HTTP+Servers%2C+Shells%2C+Concurrency;42+%2F+1337+(UM6P)+Rabat+%E2%80%A2+Cadet" alt="Typing SVG" />
</p>

<p align="center">
  <a href="mailto:oualidobbad@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://www.linkedin.com/in/oualid-obbad/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://profile.intra.42.fr/users/oobbad"><img src="https://img.shields.io/badge/42%20Intra-000000?style=for-the-badge&logo=42&logoColor=white" alt="42 Intra" /></a>
  <img src="https://komarev.com/ghpvc/?username=obbad-dev&style=for-the-badge&color=F7A41D&label=VIEWS" alt="Profile views" />
</p>

<!-- ═══════════════════════ 42 BADGE ═══════════════════════ -->

<h3 align="center">42 Cursus — live progress</h3>

<p align="center">
  <a href="https://profile.intra.42.fr/users/oobbad">
    <img src="https://badge.mediaplus.ma/binary/oobbad" alt="Oualid Obbad — 42 level badge" width="440" />
  </a>
</p>

<p align="center"><sub>Name, grade and level update automatically from the 42 intranet.</sub></p>

---

<!-- ═══════════════════════ WHOAMI ═══════════════════════ -->

## `whoami`

```console
$ ./minishell
minishell> whoami
```

```cpp
#include <string>
#include <vector>

class OualidObbad : public SoftwareEngineer {
  public:
    const std::string name    = "Oualid Obbad";
    const std::string login   = "oobbad";
    const std::string school  = "42 / 1337 (UM6P) — Rabat, Morocco";
    const std::string status  = "Open to a software engineering internship";

    std::vector<std::string> core() const {
        return { "C", "C++98", "Java" };
    }

    std::vector<std::string> focus() const {
        return { "Backend Development", "Spring", "PostgreSQL", "Docker", "Linux" };
    }

    std::string buildsThingsLike() const {
        return "an HTTP/1.1 server on a non-blocking epoll loop, "
               "a POSIX shell, a layered Java app over PostgreSQL, "
               "and a multi-container Docker stack — all from scratch";
    }

    std::string philosophy() const {
        return "Understand it end to end, or you don't understand it.";
    }
};
```

---

<!-- ═══════════════════════ STACK ═══════════════════════ -->

## Tech Stack

<table width="100%">
  <tr>
    <td width="170"><b>Core Languages</b></td>
    <td><img src="https://skillicons.dev/icons?i=c,cpp,java&theme=dark" alt="C, C++, Java" height="42" /></td>
  </tr>
  <tr>
    <td><b>Backend</b></td>
    <td><img src="https://skillicons.dev/icons?i=spring,maven,postgres,mysql&theme=dark" alt="Spring, Maven, PostgreSQL, MySQL" height="42" /></td>
  </tr>
  <tr>
    <td><b>Systems &amp; DevOps</b></td>
    <td><img src="https://skillicons.dev/icons?i=linux,docker,nginx,bash,git,github,vim&theme=dark" alt="Linux, Docker, NGINX, Bash, Git, GitHub, Vim" height="42" /></td>
  </tr>
  <tr>
    <td><b>Secondary</b></td>
    <td><img src="https://skillicons.dev/icons?i=js,html,css,python&theme=dark" alt="JavaScript, HTML, CSS, Python" height="42" /></td>
  </tr>
</table>

<sub><b>Also:</b> JDBC · HikariCP · JUnit 5 · Mockito · Spring JDBC · POSIX threads · Sockets &amp; <code>epoll</code> · CGI · Make</sub>

---

<!-- ═══════════════════════ PROJECTS ═══════════════════════ -->

## Featured Projects

<table width="100%">
<tr>
<td width="50%" valign="top">

### [webserv](https://github.com/obbad-dev/webServ)
**HTTP/1.1 web server in C++98** · *team of 2*

An NGINX-inspired server written from scratch, no external libraries. Single-threaded non-blocking event loop on `epoll()`, `GET`/`POST`/`DELETE`, a hand-written tokenizer and parser for an NGINX-style config, virtual hosting, CGI execution, multipart uploads, autoindex, custom error pages and redirects.

<img src="https://img.shields.io/badge/C++98-00599C?style=flat-square&logo=cplusplus&logoColor=white" /> <img src="https://img.shields.io/badge/epoll-F7A41D?style=flat-square" /> <img src="https://img.shields.io/badge/Sockets-161b22?style=flat-square" /> <img src="https://img.shields.io/badge/CGI-161b22?style=flat-square" />

<sub>Network programming · I/O multiplexing · implementing a protocol from an RFC · parser design</sub>

</td>
<td width="50%" valign="top">

### [pool_java_part2](https://github.com/obbad-dev/pool_java_part2)
**Java backend engineering**

Four Maven modules covering a real backend's layers: a chat app on a normalized PostgreSQL schema with a JDBC repository layer and HikariCP pooling, JUnit 5 + Mockito tests against an embedded DB, a **custom ORM** driven by reflection and annotations, and DI through the Spring container.

<img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" /> <img src="https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=spring&logoColor=white" /> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" /> <img src="https://img.shields.io/badge/JUnit%205-25A162?style=flat-square&logo=junit5&logoColor=white" />

<sub>Layered architecture · relational modelling · dependency injection · testing discipline</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [minishell](https://github.com/obbad-dev/minishell)
**POSIX shell in C** · *team of 2*

A Bash-like shell built with no parsing libraries. Full pipeline — lexer → expansion → parser → execution — with pipes, all redirections, heredocs, quoting rules, `$VAR` and `$?` expansion, seven builtins, Bash-accurate signals, and a custom tracking allocator for leak-free cleanup.

<img src="https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white" /> <img src="https://img.shields.io/badge/Processes-F7A41D?style=flat-square" /> <img src="https://img.shields.io/badge/Signals-161b22?style=flat-square" /> <img src="https://img.shields.io/badge/Readline-161b22?style=flat-square" />

<sub>Process &amp; file-descriptor management · tokenizer and parser design · memory discipline</sub>

</td>
<td width="50%" valign="top">

### [inception](https://github.com/obbad-dev/inception-42)
**Containerized infrastructure**

A multi-service stack where every service runs in its own container from a hand-written Dockerfile: NGINX reverse proxy with TLSv1.2/1.3 as the sole entrypoint, WordPress on PHP-FPM, MariaDB, Redis, Adminer, FTP and local DNS — on an isolated bridge network with Docker secrets and persistent volumes.

<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" /> <img src="https://img.shields.io/badge/NGINX-009639?style=flat-square&logo=nginx&logoColor=white" /> <img src="https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white" /> <img src="https://img.shields.io/badge/TLS-F7A41D?style=flat-square" />

<sub>Container orchestration · service isolation · reverse proxying &amp; TLS · secret handling</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [cub3D](https://github.com/obbad-dev/cub3d_mandatory)
**Raycasting 3D engine in C**

A Wolfenstein-style renderer turning a 2D tile map into a navigable 3D view: DDA raycasting with horizontal/vertical intersection selection, per-direction wall textures, a real-time loop at 1920×1080, a minimap, and a fully validated `.cub` scene parser.

<img src="https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white" /> <img src="https://img.shields.io/badge/Raycasting-F7A41D?style=flat-square" /> <img src="https://img.shields.io/badge/MiniLibX-161b22?style=flat-square" />

<sub>Applied geometry · real-time rendering · modular C design</sub>

</td>
<td width="50%" valign="top">

### [philosophers](https://github.com/obbad-dev/philosophers_42)
**Concurrency in C**

The Dining Philosophers problem under strict timing constraints: deadlock avoidance via parity-ordered acquisition, race-free shared state, a monitoring thread detecting starvation at millisecond resolution, and clean shutdown of every thread.

<img src="https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white" /> <img src="https://img.shields.io/badge/pthreads-F7A41D?style=flat-square" /> <img src="https://img.shields.io/badge/Mutexes-161b22?style=flat-square" />

<sub>Multithreading · synchronization primitives · deadlock &amp; race reasoning</sub>

</td>
</tr>
</table>

<details>
<summary><b>More on this profile</b></summary>

<br>

- **C++98 / OOP** — [CPP00–CPP09](https://github.com/obbad-dev?tab=repositories&q=CPP): inheritance, polymorphism, operator overloading, exceptions, templates, STL containers and iterators
- **C fundamentals** — [libft](https://github.com/obbad-dev/libft) · [ft_printf](https://github.com/obbad-dev/ft_printf) · [push_swap](https://github.com/obbad-dev/pushSwap) · [minitalk](https://github.com/obbad-dev/minitalk) · [so_long](https://github.com/obbad-dev/so_long)
- **Java fundamentals** — [pool_java](https://github.com/obbad-dev/pool_java): OOP, collections, exceptions, I/O and streams, multithreading, JAR packaging, JDBC
- **Databases & scripting** — [Celestial_Bodies_Database](https://github.com/obbad-dev/Celestial_Bodies_Database) · [database workshops](https://github.com/obbad-dev/worshop_of_data_base) · [Bash scripting](https://github.com/obbad-dev/basic_bash_scripting)
- **Web basics** — [html-css](https://github.com/obbad-dev/html-css): responsive layouts with Flexbox and Grid

</details>

---

<!-- ═══════════════════════ STATS ═══════════════════════ -->

## GitHub Activity

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=obbad-dev&theme=github_dark" height="200" alt="Languages by repository" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=obbad-dev&theme=github_dark" height="200" alt="Languages by commit" />
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=obbad-dev&theme=github_dark" width="87%" alt="Profile summary" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=obbad-dev&theme=tokyonight&hide_border=true&background=0D1117&ring=F7A41D&fire=F7A41D&currStreakLabel=F7A41D&sideLabels=c9d1d9&dates=6e7681" height="180" alt="Contribution streak" />
</p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/obbad-dev/obbad-dev/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/obbad-dev/obbad-dev/output/github-contribution-grid-snake.svg" />
  <img src="https://raw.githubusercontent.com/obbad-dev/obbad-dev/output/github-contribution-grid-snake.svg" alt="Contribution snake" width="100%" />
</picture>

---

<!-- ═══════════════════════ NOW ═══════════════════════ -->

## Currently

```diff
+ Learning Spring Boot — from the Spring core container toward REST APIs and persistence
+ Deepening PostgreSQL — query design, indexing, transaction behaviour
+ Continuing the 42 cursus at 1337 (UM6P) Rabat
! Looking for a software engineering internship — backend or systems
```

<p align="center">
  <a href="mailto:oualidobbad@gmail.com"><img src="https://img.shields.io/badge/Let's%20talk-oualidobbad@gmail.com-F7A41D?style=for-the-badge&logo=minutemailer&logoColor=white" alt="Contact" /></a>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:F7A41D,55:1f2937,100:0d1117&height=110&section=footer" width="100%" alt="" />
