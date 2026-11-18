# Danil Tulgaev

<p align="center">
  <strong>Backend Developer</strong><br/>
  Building backend systems, concurrent applications and data-processing tools.
</p>

<p align="center">
  <a href="https://github.com/bug00n">
    <img src="https://img.shields.io/badge/ GitHub-181717?style=flat&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white" alt="Go"/>
  <img src="https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white" alt="C++"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black" alt="Linux"/>
</p>

---

## About

I'm a backend developer interested in the engineering behind reliable and efficient services: concurrency, networking, data processing, storage and system performance.

I have a strong C++ background and am currently focusing on **Go backend development**. I enjoy understanding how things work under the hood and building projects where architecture, synchronization and performance matter.

- **Experience:** C++ Backend Intern at Yandex
- **Current focus:** Go, backend architecture, concurrency and testing
- **Background:** Competitive programming and algorithms; prize-winner of the All-Russian Olympiad in Informatics
- **Education:** HSE University, Faculty of Computer Science

## Experience

### Yandex — C++ Backend Intern

Worked on a backend service in the Yandex Crypto team, which processes large volumes of event and log data.

- Developed and updated C++ logic for processing new log formats.
- Used YQL/SQL to analyze data and compare processing results between old and new event formats.
- Added and checked handlers, configuration changes and tests as part of staged rollouts.
- Worked with a MapReduce-based data-processing service.

## Selected projects

### [StreamForge](https://github.com/bug00n/StreamForge) · Go

An experimental in-process MapReduce library written in Go.

- Splits input data into map tasks and processes them with worker goroutines.
- Groups intermediate values by key using hash-based shuffle partitioning.
- Runs reduce tasks through a separate worker pool.
- Uses typed APIs, channels and synchronization to coordinate job execution and graceful engine shutdown.

### [HighLoad-Systems](https://github.com/bug00n/HighLoad-Systems) · C++ / Python

A collection of backend and systems programming projects focused on networking, concurrency and performance.

- **[Sharded In-Memory Cache](https://github.com/bug00n/HighLoad-Systems/tree/main/cache)** — C++20 cache with sharding, per-shard synchronization, worker threads and asynchronous operations.
- **[TCP Messenger](https://github.com/bug00n/HighLoad-Systems/tree/main/messager-cpp)** — asynchronous TCP chat server built with Boost.Asio.
- **[HTTP Server](https://github.com/bug00n/HighLoad-Systems/tree/main/HTTP-server-cpp)** — HTTP request parsing, socket programming, multithreading and TTL cache.
- **[Account Manager API](https://github.com/bug00n/HighLoad-Systems/tree/main/account-manager-py)** — FastAPI service with PostgreSQL, Redis and JWT authentication.

### [Go Bank Account Service](https://github.com/bug00n/Go-Bank-Account-Service) · Go

A small HTTP backend service for managing bank accounts.

- REST API built with the standard `net/http` package.
- SQLite persistence through `database/sql`.
- Account operations, request validation and transactional transfer logic in the storage layer.

### [HackathonPetrolCode](https://github.com/bug00n/HackathonPetrolCode) · Python

A local decision-support application developed as a team hackathon project. It combines model-based calculations, historical data analysis and constraint checks for industrial process scenarios.

## Tech stack

| Area | Technologies |
| --- | --- |
| **Languages** | Go, C++17/20, Python |
| **Backend & APIs** | net/http, FastAPI, REST, JSON |
| **Concurrency & networking** | Goroutines, channels, synchronization, multithreading, Boost.Asio, TCP/IP |
| **Databases** | PostgreSQL, SQLite, Redis, SQL, YQL |
| **Tools** | Linux, Git, Docker, CMake, Make |

## Interests

Backend engineering · High-load systems · Distributed data processing · Concurrency · Networking · Caching

---

<p align="center">
  <i>Always learning, building and digging into how systems work.</i>
</p>
