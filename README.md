
# 🖥️ Operating Systems

This repository is dedicated to revisiting and reinforcing the core concepts of **Operating Systems** through theory, system-level programming, and project-based learning using **C** and **Linux**.  
It supports my broader Cloud Computing roadmap by focusing on the mechanisms that underpin process management, memory, and system calls — essential knowledge for designing efficient cloud-native systems.

---

## 📁 Repository Structure

```bash
operating-systems/
├── theory/          # 📚 Notes on OS theory and internal mechanisms
│   ├── processes.md
│   ├── system_calls.md
│   ├── memory_management.md
│   ├── threads_scheduling.md
│   └── file_systems.md
│
├── practice/        # 💻 Small C/Linux programs to illustrate concepts
│   ├── fork_exec/
│   ├── file_io/
│   ├── threads_mutexes/
│   └── signals/
│
├── projects/        # 🚧 Full-featured system-level projects
│   ├── mini-shell/
│   ├── round-robin-scheduler/
│   ├── multithreaded-downloader/
│   └── memory-allocator/
│
└── README.md
```

---

## 🎯 Objectives

- Deepen understanding of how modern operating systems manage resources
- Practice using **system calls** for I/O, process, and memory control
- Simulate scheduling and memory allocation strategies
- Bridge the gap between low-level programming and systems design

---

## 📚 Theory Coverage

Inside `/theory` you'll find:
- 🔹 Process lifecycle, states, and scheduling
- 🔹 System calls (`fork()`, `exec()`, `wait()`, `open()`, etc.)
- 🔹 Memory management: heap, stack, paging, segmentation
- 🔹 File systems and disk I/O
- 🔹 Concurrency: threads, race conditions, synchronization mechanisms

---

## 💻 Practice Programs

The `/practice` folder includes:
- System call exercises (fork, exec, pipe, file handling)
- Thread and mutex usage examples with `pthreads`
- Signal handling and basic scheduling logic

---

## 🚀 Projects

The `/projects` folder showcases real-world applications of OS principles:
- 📌 `mini-shell`: a functional Unix shell written in C
- 📌 `round-robin-scheduler`: simulate CPU time-sharing
- 📌 `multithreaded-downloader`: basic file downloader using threads
- 📌 `memory-allocator`: simulate malloc/free functionality

Each project includes:
- `README.md` with description, how to build/run
- Example inputs and outputs
- Optional extensions for further practice

---

## 🛠️ Technologies Used

- `C` (main language for system-level implementation)
- `Bash` (script automation, testing)
- `Linux` (Ubuntu, WSL, or native)

---

## 📎 Notes

This repository emphasizes depth and correctness over breadth. It is intended to reinforce practical understanding of operating systems and prepare for topics like **process containers**, **virtualization**, and **cloud orchestration**.

---
