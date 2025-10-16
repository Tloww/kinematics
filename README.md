# Forward Kinematics Task 

##  Task Description
In this task, we applied **Forward Kinematics** to a 2D robotic arm with three links.  
The goal was to calculate the **end-effector position (x, y)** based on given joint angles and link lengths using trigonometric equations.

---

## Parameters
- **Link lengths**:  
  - \(L1 = 15)  
  - \(L2 = 10)  
  - \(L3 = 4)  

  **Assumed joint angles**:  
  - \(q1 = 0)  
  - \(q2 = 45)  
  - \(q3 = -20)  



##  Equations
The forward kinematics equations for a 2D 3-link arm:

\[
x = L1 \cos(q1) + L2 \cos(q1 + q2) + L3 \cos(q_1 + q2 + q3)
\]

\[
y = L1 \sin(q_1) + L2 \sin(q1 + q2) + L3 \sin(q1 + q2 + q3)
\]

---


![Solution](https://raw.githubusercontent.com/Tloww/kinematics/main/mech_task.jpg)

##  Result
After substituting the values:

\[
(x, y) \approx (25.7,\ 8.7)\ \text{cm}
\]

So, the **end-effector position** of the robotic arm is approximately **25.7 cm in X** and **8.7 cm in Y**.

---
