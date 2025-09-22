# School Timetabling & Supply Chain Optimization problems


This repository contains the modeling and solution of optimization problems in **Operations Research**.  
The work was developed as part of the *Operations Research* course project at the **Department of Electrical and Computer Engineering, Aristotle University of Thessaloniki**.


## 📌 Project Overview 

The project consists of two main optimization problems:

### 1. 🗓️ Weekly Class Schedule Design
Mr. Προγραμματούλης is responsible for designing the weekly schedule of two classes in a school.  
Constraints include:
- Common teachers for both classes (except Mathematics & Physical Education).  
- All lessons last **2 hours**.  
- Time slots:  
  - 08:00–10:00  
  - 10:15–12:15  
  - 14:00–16:00  
  - 16:15–18:15  
- **Special constraints**:
  - Physical Education must always take place **Thursday 14:00–16:00**.  
  - Monday 08:00–10:00 reserved for weekly study planning.  
  - Some teachers have unavailability (e.g., no Math teacher Monday morning, no Biology teacher Wednesday).  
  - Each class can have at most **one lesson per subject per day**.  

**Objective:**  
Formulate and solve a scheduling problem that satisfies all constraints.

---

### 2. 🏭 Optimal Warehouse Location
A company plans to open new warehouses to serve **12 sales centers**.  

- Each warehouse has:
  - A **fixed installation cost**.  
  - A **capacity limit**.  
- Each sales center has:
  - A **demand (tons)** that must be fully satisfied.  
- Deliveries incur a **transportation cost**, depending on distance.  
- Some deliveries are **impossible** (denoted ∞).  

**Objective:**  
Decide which warehouses to open and how to allocate demands to minimize **total installation + transportation cost**, while covering all demands.
