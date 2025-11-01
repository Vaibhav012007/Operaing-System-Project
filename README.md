# Disk Scheduling Simulator

The **Disk Scheduling Simulator** is a web-based interactive application that demonstrates how operating systems manage and schedule disk I/O requests to minimize seek time and improve overall system performance.  
The system visually represents disk head movement and calculates the **total head movement** for each algorithm, enhancing user understanding of how different disk scheduling techniques affect **disk utilization** and **I/O efficiency**.

The simulator implements six major disk scheduling algorithms:
- **FCFS (First Come First Serve)**
- **SSTF (Shortest Seek Time First)**
- **SCAN (Elevator Algorithm)**
- **C-SCAN (Circular SCAN)**
- **LOOK**
- **C-LOOK**

---

##  Objectives
1. To simulate and compare major disk scheduling algorithms.  
2. To provide an **interactive visualization** of disk head movements.  
3. To calculate and display **total seek time** for each algorithm.  
4. To enhance **practical understanding** of disk scheduling mechanisms used in Operating Systems.

---

##  Project Overview
Disk scheduling plays a vital role in optimizing system performance by determining the **most efficient order** to service disk I/O requests.  
Since the CPU operates much faster than disk access, efficient disk scheduling is critical to minimize:
- **Seek Time** (movement of the read/write head),
- **Rotational Delay**, and  
- **Overall Disk Latency**.

This project simulates and visualizes how each scheduling algorithm handles a given set of I/O requests.  
Users can:
- Input a **custom list of disk cylinder requests**.  
- Specify the **initial head position**.  
- Observe a **step-by-step animation** of the head movement.  
- Compare the **total head movement** and performance across all algorithms.

The system bridges the gap between theoretical Operating System concepts and practical visualization, allowing students and learners to **experiment, analyze, and understand** how scheduling strategies influence:
- System response time,  
- Head travel distance, and  
- Avoidance of starvation in I/O request handling.

---

##  Features
- Interactive web interface with real-time visualization  
- Supports six major disk scheduling algorithms  
- User input for custom disk request sequences  
- Calculation and comparison of total seek time  
- Graphical representation of head movement across cylinders  
- Educational tool for OS learners and researchers  

---
