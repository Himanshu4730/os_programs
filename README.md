# Operating Systems Lab (CEC301/CSC301)

A collection of programs and simulations for the Operating Systems lab, covering core OS concepts from process creation to file allocation. Implemented in a Jupyter notebook (`os.ipynb`).

## List of Programs

| S.No. | Title of Program |
|-------|------------------|
| 1 | Introduction to Linux System Calls, Process Creation using `fork()`, `exec()` and `wait()` |
| 2 | Thread Creation and Management using POSIX Threads (pthreads) |
| 3 | CPU Scheduling Algorithms: FCFS, SJF, Priority and Round Robin |
| 4 | Process Synchronization: Producer-Consumer Problem using Semaphores |
| 5 | Process Synchronization: Readers-Writers Problem using Semaphores |
| 6 | Dining Philosophers Problem using Semaphores |
| 7 | Deadlock Avoidance using Banker's Algorithm |
| 8 | Contiguous Memory Allocation: First Fit, Best Fit and Worst Fit |
| 9 | Page Replacement Algorithms: FIFO, LRU and Optimal |
| 10 | Disk Scheduling Algorithms: FCFS, SSTF, SCAN and C-SCAN |
| 11 | File Allocation Methods: Contiguous, Linked and Indexed Allocation |

## Repository Structure

| File | Description |
|------|-------------|
| `os.ipynb` | Notebook containing the lab programs, outputs and explanations |
| `README.md` | Project overview |

## Requirements
- Python 3.8+
- Jupyter Notebook or JupyterLab
- A Linux environment (or WSL / Linux VM) if running programs that use system calls such as `fork()`, `exec()`, `wait()` and pthreads

```bash
pip install notebook
```

## Topics Covered
- **Processes and threads:** system calls, fork/exec/wait, pthreads
- **CPU scheduling:** FCFS, SJF, Priority, Round Robin
- **Synchronization:** semaphores, Producer-Consumer, Readers-Writers, Dining Philosophers
- **Deadlocks:** Banker's Algorithm
- **Memory management:** First/Best/Worst Fit, FIFO/LRU/Optimal page replacement
- **Storage:** disk scheduling (FCFS, SSTF, SCAN, C-SCAN) and file allocation methods

## Author
**Your Name**: Himanshu Mathpal

## License
This project is licensed under the MIT License.
