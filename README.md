# 🚗 Smart Parking Management System

### 🧠 *A collaborative web-based project demonstrating core Data Structures and Algorithms (DSA) concepts for efficient and priority-based vehicle parking management.*

---

## 📘 **Overview**
The **Smart Parking Management System** automates vehicle parking using efficient DSA-based logic.  
It dynamically assigns the nearest available parking slot, manages **normal and VIP/emergency vehicles** through queues and priority queues, records activity logs, and stores all data persistently in the browser — all within a single web page.  

Developed as part of the **Integrated M.Tech Software Engineering** program at **Vellore Institute of Technology (VIT)**, this project showcases the real-world application of **Data Structures and Algorithms (DSA)** through modern web technologies.

---

## 👨‍💻 **Team Members**
| Name | Role | Contribution |
|------|------|---------------|
| **Shivanesh** | DSA Integration & JavaScript Logic | Implemented Queue, Stack, Sorting, Priority Queue, and File Handling logic. |
| **Leela Avinash** | Frontend & UI Design | Designed page layout and improved user experience using CSS. |
| **Praveenkumar** | Testing & Debugging | Performed functionality testing and logic validation. |
| **Thushar** | Data Flow & Optimization | Optimized script execution and slot allocation process. |
| **Dharshan** | Documentation & Presentation | Created report, slides, and maintained overall documentation. |

---

## ⚙️ **Key Features**
✅ Automatic slot allocation using Sorting and Greedy Algorithms  
✅ Dual queue system for **normal and VIP/emergency vehicles**  
✅ Priority Queue ensures immediate allocation for urgent cases  
✅ Real-time activity tracking using Stack (LIFO)  
✅ Vehicle search using Linear Search  
✅ Persistent data storage via LocalStorage  
✅ Clean, interactive, and user-friendly interface  

---

## 🧩 **DSA Concepts Implemented**

| **Concept** | **Usage in Project** |
|--------------|----------------------|
| **Queue / Priority Queue** | Normal vehicles handled using FIFO; **VIP or emergency vehicles** prioritized with a Priority Queue. |
| **Stack** | Maintains activity logs for vehicle entry and exit (LIFO principle). |
| **Sorting** | Arranges available slots in ascending order of slot ID. |
| **Greedy Algorithm** | Instantly selects the nearest available slot for efficiency. |
| **Linear Search** | Locates a vehicle using its vehicle number. |
| **File Handling (LocalStorage)** | Stores parking data and logs permanently in the browser. |

---

## 💻 **Technologies Used**
- **HTML5** → Page structure and layout  
- **CSS3** → Styling, color coding, and responsive interface  
- **JavaScript (ES6)** → Logic, DSA operations, and LocalStorage handling  

---

## 🧠 **System Workflow**
1. Vehicle enters → Slot availability checked.  
2. If available → Allocated using Sorting + Greedy Algorithm.  
3. If full → Vehicle added to waiting queue.  
   - **VIP or Emergency Vehicles** added to a **Priority Queue** and served first.  
4. When a slot is freed → Highest-priority or earliest waiting vehicle is allotted.  
5. All actions recorded in a Stack-based activity log.  
6. Data stored persistently using LocalStorage for continuity.  

---

## 🧮 **Example Code Snippets**

**Queue + Priority Queue**
```js
// Normal queue
this.waitingQueue.push(vehicle);
const nextVehicle = this.waitingQueue.shift();

// Priority-based queue (VIP or Emergency)
this.waitingQueue.sort((a, b) => b.priority - a.priority);
```

**Sorting + Greedy Algorithm**
```js
const nearestSlot = available.sort((a, b) => a.id - b.id)[0];
```

**File Handling (LocalStorage)**
```js
localStorage.setItem('parkingData', JSON.stringify(this.slots));
const data = JSON.parse(localStorage.getItem('parkingData'));
```

---

## 🎨 **Interface Highlights**
- **Color-coded slots:**  
  🟩 Available | 🟥 Occupied | 🟨 Waiting | ⭐ VIP/Emergency Allocated  
- **Responsive Layout:** Designed using CSS Grid and Flexbox.  
- **Dynamic Updates:** JavaScript updates slot status, queue order, and activity log in real time.  

---

## 🚀 **How to Run**
1. Clone or download this repository.  
2. Open the file **`Smart Parking.html`** in any modern browser (Chrome recommended).  
3. The project runs completely **offline** — no external server setup required.  

---

## 🏁 **Conclusion**
This collaborative project demonstrates the **real-world application of DSA** in solving everyday challenges like parking management.  
By integrating **Queue, Stack, Sorting, Greedy Algorithm, Linear Search**, and **File Handling**, along with a **Priority Queue for VIP and Emergency vehicles**, the system achieves fairness, speed, and reliability.  

It highlights how DSA-driven logic can power efficient, data-backed automation systems.  

---

## 👥 **Developed By**
**Team SmartCoders**  
Integrated M.Tech – Software Engineering  
**Vellore Institute of Technology (VIT)**  



