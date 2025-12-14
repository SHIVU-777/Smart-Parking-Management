# 🚗 Smart Parking Management System

Built with a focus on real-world parking systems used in malls, hospitals, and smart city environments.

A **web-based smart parking solution** that uses **Data Structures and Algorithms (DSA)** to efficiently manage vehicle parking with **priority handling** for VIP and emergency vehicles.

🔗 **Live Demo:** [https://smart-parking-system7.netlify.app/](https://smart-parking-system7.netlify.app/)

---

## 📌 Problem Statement

Traditional parking systems often suffer from:

* Inefficient slot allocation
* No priority handling for emergency vehicles
* Poor tracking of parking activity

This project addresses these challenges by applying **core DSA concepts** to automate parking allocation, intelligently manage waiting vehicles, and maintain **persistent parking records** — all within a lightweight, **single-page web application**.

---

## 💡 Solution Overview

The system dynamically assigns the **nearest available parking slot**, manages **normal and priority vehicles** using queues, and records parking activity in real time.

All data is stored persistently in the browser using **LocalStorage**, enabling continuity **without any backend server**.

This demonstrates how **DSA-driven logic** can be applied to real-world environments such as:

* Malls
* Hospitals
* Office complexes
* Smart city parking systems

---

## ⚙️ Key Features

* Automatic parking slot allocation using **Sorting + Greedy Algorithm**
* Separate handling for **normal** and **VIP/emergency** vehicles
* **Priority Queue** ensures urgent vehicles are served first
* **Stack-based activity log** for entry and exit tracking
* Vehicle lookup using **Linear Search**
* Persistent data storage using **LocalStorage**
* Clean, responsive, and interactive user interface

---

## 🧠 Data Structures & Algorithms Used

| Concept          | Industry Use in System                     |
| ---------------- | ------------------------------------------ |
| Queue            | Manages normal vehicle waiting line (FIFO) |
| Priority Queue   | Handles VIP and emergency vehicles         |
| Stack            | Maintains activity logs (LIFO)             |
| Sorting          | Orders available slots by proximity        |
| Greedy Algorithm | Allocates nearest available slot           |
| Linear Search    | Searches vehicle records                   |
| LocalStorage     | Persistent client-side data storage        |

---

## 🛠️ Technologies Used

* **HTML5** – Application structure
* **CSS3** – Styling and responsive layout
* **JavaScript (ES6)** – Core logic, DSA implementation, and storage handling

---

## 🔄 System Workflow

1. Vehicle enters the system
2. Slot availability is checked
3. If available → nearest slot allocated using sorting + greedy logic
4. If full → vehicle added to waiting queue
5. VIP/emergency vehicles enter priority queue
6. When a slot is freed → highest-priority or earliest waiting vehicle is allocated
7. All activities logged and stored persistently

---

## 🚀 How to Run the Project

1. Clone or download the repository
2. Open `Smart Parking.html` in any modern browser (Chrome recommended)
3. No server or backend setup required — runs completely offline

---

## 🏁 Conclusion

This project demonstrates how **fundamental Data Structures and Algorithms** can be effectively applied to solve **real-world system problems**.

By combining **queues, priority queues, stacks, sorting, and greedy algorithms** with modern web technologies, the system delivers a **fair, efficient, and scalable parking management solution** suitable for industry-level applications.

---
## 🔮 Future Enhancements
- Backend integration with database (MongoDB / PostgreSQL)
- Real-time updates using WebSockets
- Mobile app version
- IoT sensor integration for real-time slot detection

## 👥 Team

**Team SmartCoders**
Integrated M.Tech – Software Engineering
Vellore Institute of Technology (VIT)

---
