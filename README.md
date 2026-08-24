## Hi, I'm @HoangMNguyen 👋

- 👀 I'm interested in programming fun projects, making great espresso, and other stuffs :)
- 🎓 M.S. in Computer Science, Georgia Tech (OMSCS) — focused on **database internals, distributed systems, and backend engineering**
- 💞️ I'm looking to collaborate on any projects, so please feel free to reach out!
- 📫 You can reach me through my email: hoangmnguyen.work@gmail.com

## 🧠 Featured project

**[ARC-AGI Solver](https://github.com/HoangMNguyen/arc-agi-solver)** — a symbolic, search-based agent for ARC-AGI abstraction-and-reasoning puzzles: observation-driven hypothesis generation over a transformation registry, validated by breadth-first search across training examples. Pure reasoning, no training data.

## 💼 Professional projects

**CCI Clinical Reporting & Automation Suite** *(private — available on request)* — a suite of four desktop applications for clinical trial reporting at Penn Medicine's CCI, built on a **single shared headless backend**. The flagship Clinical Reporting Tool is a configurable report builder over Corelisting/CSV/Excel data (join, filter, and comparison configuration with reusable saved settings); companion apps automate enrollment logs, DSMB safety reports, and Clockify time-tracking dashboards, AE/DLT safety listings, and Medidata SDS peer-review error reports. Unit- and integration-tested with pytest, Ruff-linted, and packaged as standalone executables. An earlier public iteration of the automation tooling is at [CCI-Automation](https://github.com/HoangMNguyen/CCI-Automation). *Python, PySide6, pandas, NumPy, xlsxwriter, REST APIs, pytest, PyInstaller.*

## 🎓 Graduate coursework portfolio

Coursework from the Georgia Tech OMSCS program. **These repositories are private** in line with Georgia Tech's academic policy — I'm happy to grant read access to recruiters and collaborators on request.

`C/C++17` · `Java` · `Python` · `SQLite` · `gRPC & Protocol Buffers` · `POSIX threads/IPC & sockets` · `Docker` · `CMake` · `LLVM` · `Gradle` · `pandas` · `Linux`

### Database & systems programming

| Course | What I built | Tools & tech |
|---|---|---|
| **CS 6422 — Database System Implementation** | Core components of a relational DBMS built from scratch across five labs: page-based storage and file layout, buffer management, and a query execution engine with physical operators — all developed and tested in a containerized Linux environment | C++17, CMake, Docker & Compose, Linux |
| **CS 6200 — Graduate Intro to Operating Systems** | Server-side systems in C: a multithreaded file-transfer server and client (boss–worker thread pool over POSIX sockets and a custom protocol); a multi-process caching proxy where processes coordinate through shared memory, semaphores, and message queues; and a distributed file system with client–server synchronization over gRPC | C, pthreads, POSIX IPC (shared memory, semaphores, message queues), Berkeley sockets, gRPC, Protocol Buffers, Make, Vagrant |
| **CS 6290 — High Performance Computer Architecture** | Performance experiments on a cycle-accurate CPU simulator: branch predictor modifications, cache hierarchy and memory studies, and multicore cache-coherence analysis — with findings quantified in written reports | C++, SESC simulator, Linux VMs |

### Networking & infrastructure

| Course | What I built | Tools & tech |
|---|---|---|
| **CS 6250 — Computer Networks** | Distributed control-plane algorithms implemented from the ground up: a spanning tree protocol and a distance-vector routing protocol with negative-cycle handling, validated across emulated network topologies; SDN-based network simulations | Python, Mininet, SDN |
| **CS 6340 — Software Analysis & Testing** | Program-analysis tooling on the LLVM toolchain: custom IR instrumentation passes, a coverage-guided fuzzer built in three stages, and dataflow analyses over LLVM IR | C++, LLVM, CMake |

### Software engineering & data

| Course | What I built | Tools & tech |
|---|---|---|
| **CS 6300 — Software Development Process** | An Android app taken through four structured deliverables — requirements, UML design, implementation, and testing — plus a team-built job-comparison app backed by SQLite (`SQLiteOpenHelper` persistence layer, Espresso instrumented test suite) and TDD assignments with unit, white-box, and black-box tests under CI | Java, Android SDK, SQLite, Gradle, JUnit, Espresso, Git |
| **CS 7646 — Machine Learning for Trading** | Decision-tree, random-tree, and bagging ensemble learners implemented from scratch (no ML libraries); a market simulator that processes order books into portfolio valuations; portfolio statistics and optimization | Python, pandas, NumPy, matplotlib |
| **CS 7637 — Knowledge-Based AI** | A suite of reasoning agents — classification, diagnosis, planning, and NLP — culminating in the ARC-AGI solver featured above | Python, NumPy, scikit-image, OpenCV |

**Also completed:** CS 6515 Graduate Algorithms (dynamic programming, divide & conquer, graph algorithms, correctness proofs) · CS 6750 Human-Computer Interaction (semester-long UX research and evaluation project) · CS 8001 Java OOP seminar.

<!---
HoangMNguyen/HoangMNguyen is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
