# 🚖 Ride-Sharing Simulator (Python)

## 📌 Concept
This project simulates a **ride-sharing system** where:
- Riders are managed in a **queue (FIFO)**.
- Drivers are assigned using a **priority queue (heapq)**:
  - Nearest driver gets priority.
  - If two drivers are at the same distance, the **higher-rated driver** is chosen.
- Each completed ride is recorded in a **ride history**.

---

## ✨ Features
- 📥 Rider queue using `deque`  
- 🚗 Driver priority queue using `heapq`  
- 🎯 Matching algorithm → Nearest + Best driver first  
- 📝 Ride history tracking  

---

## 🛠️ How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/YourUsername/ride-sharing-simulator.git


## 🚀 Demo Screenshot

Here is the output of the Ride-Sharing Dispatch Simulator:

![Simulator Output](screenshots/output.png)
