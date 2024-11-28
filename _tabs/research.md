---
# the default layout is 'page'
icon: fas fa-solid fa-feather
order: 2
---

## Current Research
I currently research in **Robotics** as a PhD student in the 
[Machines in Motion Laboratory](https://www.machinesinmotion.org/) 
at **New York University (NYU)**.

My current interest is optimal control and reinforcement learning 
for exoskeletons and manipulators. 
More details will be added in the future.

## Past Research
Below are some of my past research on optimal task and motion planning for mobile manipulators 
in the [Control Robotics Intelligence (CRI) Group](https://personal.ntu.edu.sg/cuong/) 
at **Nanyang Technological University (NTU Singapore)** from 2021-2024.


### 1. Mobile Manipulator Trajectory Optimization under End-effector Trajectory Continuity Constraint
* Applications: tasks requiring the end-effector to traverse a continuous 
(time-parametrized) trajectory, e.g. Mobile 3D Concrete Printing (developed at 
[Singapore Centre for 3D Printing](https://www.ntu.edu.sg/sc3dp))
* Problem: find optimal base trajectory under constraints
$$
\begin{aligned}
    &\mathbf{x}^{opt}(s) = \arg\min_{\mathbf{x}(s)} J[\mathbf{x}(s)]\\
    \text{s.t.}\quad
    &\mathbf{x}(s) \in \mathcal{X}_a, \quad 
    \dot{\mathbf{x}}(s) \in \mathcal{V}_a \quad
    \forall s \in [0,1]
\end{aligned}
$$
* Cost: weighted squared velocity (which encouraging stable motion)
* Constraints: end-effector trajectory continuity constraint, arm's joint limits, 
base's velocity limits and collision avoidance
* Solution:
1. Based on the required end-effector's trajectory and other constraints, 
find the admissible configuration spacetime for the mobile base.
2. Dynamic Programming to compute the optimal base trajectory.
3. Inverse Kinematics to find the joint trajectory of the arm.
* Paper: _Planning Optimal Trajectories for Mobile Manipulators under End-effector 
Trajectory Continuity Constraint_ (ICRA 2024) 
([PDF](https://doi.org/10.1109/ICRA57147.2024.10611630) | [Video](https://youtu.be/yyBv3xGClnk))


### 2. Mobile Manipulator Task Sequencing
* Applications: tasks involving multiple targets distributed in a large workspace 
beyond the reachability of the robotic arm, e.g. drilling in a shopfloor (inspired by 
[Airbus Shopfloor Challenge](https://robohub.org/tag/airbus-shopfloor-challenge/))
* Problem: find minimum number of base poses and shortest motion sequence to visit all targets
* Solution: two-step approach
1. Task-space clustering: based on kinematic reachability analysis,
cluster the task space into a minimum set of target clusters such that 
there exists a reachable base pose for each cluster to reach all inside targets.
2. Task sequencing: compute the shortest base sequence, shortest target sequence, 
then shortest manipulator joint trajectory to visit all targets.
* Paper: _Task-Space Clustering for Mobile Manipulator Task Sequencing_ (ICRA 2023) 
([PDF](https://doi.org/10.1109/ICRA48891.2023.10161293) | [Video](https://youtu.be/Vopupf81hYo))


## Publications
Full list: [Google Scholar](https://scholar.google.com/citations?user=6V-YHEkAAAAJ&hl=en)

2024:
* **Q.-N. Nguyen** and Q.-C. Pham, 
_"Planning Optimal Trajectories for Mobile Manipulators under End-effector Trajectory 
Continuity Constraint,"_ International Conference on Robotics and Automation (**ICRA 2024**). 
([PDF](https://doi.org/10.1109/ICRA57147.2024.10611630) | [Video](https://youtu.be/yyBv3xGClnk))

2023:
* **Q.-N. Nguyen**, N. Adrian, and Q.-C. Pham, 
_"Task-Space Clustering for Mobile Manipulator Task Sequencing,"_ 
International Conference on Robotics and Automation (**ICRA 2023**). 
([PDF](https://doi.org/10.1109/ICRA48891.2023.10161293) | [Video](https://youtu.be/Vopupf81hYo))
