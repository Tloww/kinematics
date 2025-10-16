# Forward Kinematics Task 

##  Task Description
In this task, we applied **Forward Kinematics** to a 2D robotic arm with three links.  
The goal was to calculate the **end-effector position (x, y)** based on given joint angles and link lengths using trigonometric equations.

---

## Parameters
- **Link lengths**:  
  - \(l_1 = 15\ \text{cm}\)  
  - \(l_2 = 10\ \text{cm}\)  
  - \(l_3 = 4\ \text{cm}\)  

  **Assumed joint angles**:  
  - \(q_1 = 0^\circ\)  
  - \(q_2 = 45^\circ\)  
  - \(q_3 = -20^\circ\)  



##  Equations
The forward kinematics equations for a 2D 3-link arm:

\[
x = l_1 \cos(q_1) + l_2 \cos(q_1 + q_2) + l_3 \cos(q_1 + q_2 + q_3)
\]

\[
y = l_1 \sin(q_1) + l_2 \sin(q_1 + q_2) + l_3 \sin(q_1 + q_2 + q_3)
\]

---

## 📷 Robot Arm Illustration
Below is the schematic of the robotic arm with link lengths and joint angles:

![Robot Arm]("C:\Users\HUAWEI\Downloads\mech_task.jpg")

*(Make sure to save your diagram as `arm-diagram.png` in the same GitHub repo so it displays correctly.)*

---

##  Result
After substituting the values:

\[
(x, y) \approx (25.7,\ 8.7)\ \text{cm}
\]

So, the **end-effector position** of the robotic arm is approximately **25.7 cm in X** and **8.7 cm in Y**.

---

## 🌸 Note
This solution was simplified to **2D forward kinematics** only, as requested, without including the base height or Z-axis.
