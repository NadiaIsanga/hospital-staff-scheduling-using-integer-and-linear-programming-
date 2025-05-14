# hospital-staff-scheduling-using-integer-and-linear-programming-
# 🏥 Optimizing Hospital Staff Scheduling Using Linear and Integer Programming

This project applies linear and integer programming to optimize hospital staff scheduling by minimizing costs while ensuring adequate coverage across morning, evening, and night shifts. The model accounts for full-time and part-time contracts, staff qualifications, and shift constraints.



## 📌 Summary

Developed a mathematical optimization model to improve hospital staffing using Linear and Integer Programming.  
Modeled cost-efficient schedules that respect shift coverage, contractual hours, and skill qualifications.  
Implemented and solved the model using Python’s PuLP library, producing feasible, real-world staffing solutions.

---

## 🛠️ Skills Used

- **Linear Programming (LP)**
- **Integer Programming (IP)**
- **Python (PuLP, Pandas, Matplotlib)**
  
---


---

## 🧠 Model Highlights

- **Objective Function**: Minimize total scheduling cost across all shifts.
- **Decision Variable**: Hours worked by each staff member in each shift.
- **Key Constraints**:
  - Shift coverage (minimum hours per shift)
  - Full-time/part-time hour limits
  - Qualification matching for roles
- **Solving Environment**: PuLP with CBC solver

---

## 📊 Visual Insights

- **Heatmaps**: Show staff role allocation across shifts.
- **Dual-Axis Charts**: Compare cost per hour and required hours for each role.
- **Iteration Logs**: Track solution feasibility across added constraints.

---

## 🚀 How to Run

1. Clone the repo  
   `git clone https://github.com/NadiaIsanga/hospital-staff-scheduling.git`

2. Open the notebook  
   `cd hospital-staff-scheduling/code`  
   `jupyter notebook hospital_scheduler.ipynb`

3. Run each cell to define variables, constraints, and solve the optimization problem.

---


---

## 📷 Preview

![image](https://github.com/user-attachments/assets/75d790f2-d69c-4785-a9f5-39d8dd1f5eec)

