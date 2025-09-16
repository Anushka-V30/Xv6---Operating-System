# xv6 Operating System 

This project extends the [xv6](https://pdos.csail.mit.edu/6.828/2020/xv6.html) teaching operating system with **advanced features in memory management and process scheduling**.  
The goal was to explore kernel internals, optimize resource usage, and improve overall system performance.

---

## Features Implemented

- **Lazy Memory Allocation**  
  - Pages allocated only when accessed (on-demand).  
  - Prevents unnecessary memory usage.  

- **LRU-based Page Swapping**  
  - Implemented Least Recently Used (LRU) replacement policy.  
  - Allows efficient swapping of pages between memory and disk.  

### 🔹 Scheduling Enhancements
- **Hybrid SJF / Round-Robin Scheduler**  
  - Shortest Job First for efficiency.  
  - Falls back to Round-Robin for fairness among equal-priority tasks.  


## 🛠️ Project Structure

