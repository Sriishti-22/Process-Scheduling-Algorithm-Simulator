# 🖥️ Process Scheduling Algorithm Simulator

A **GUI-based simulator** for comparative analysis of CPU scheduling algorithms.  
Built with **Python (Tkinter + matplotlib)**, this tool helps students and developers **visualize, compare, and analyze** major process scheduling strategies using **Gantt charts and performance metrics**.  

---

## 🚀 Features

- ✅ Simulates **FCFS, SJF, Priority, and Round Robin** scheduling  
- ✅ Interactive **GUI with Tkinter**  
- ✅ Dynamic **add/delete processes** functionality  
- ✅ **Gantt Chart visualization** for CPU execution timeline  
- ✅ Metrics calculation:
  - Turnaround Time  
  - Waiting Time  
  - Response Time  
- ✅ **Comparison window** to analyze performance across algorithms  
- ✅ **Best Algorithm Recommendation Engine** (based on metrics)  

---

## 📊 Implemented Algorithms

- **FCFS** (First Come First Serve) – Non-preemptive  
- **SJF** (Shortest Job First) – Preemptive  
- **Priority Scheduling** – Preemptive  
- **Round Robin** – Time-slice based  

---

## 🛠️ Tech Stack

- **Python**  
- **Tkinter** → GUI framework  
- **matplotlib** → Chart plotting  
- **OOP Design** → `Process` class + custom scheduling functions  

---

## 🏗️ System Architecture

- **Input Layer** → User inputs processes (burst time, arrival time, priority, etc.)  
- **Logic Layer** → Core scheduling algorithm implementations  
- **Output Layer** → Metrics & results  
- **Visualization Layer** → Gantt charts & comparisons  
- **Recommendation Engine** → Suggests best algorithm  
