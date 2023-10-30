---
# the default layout is 'page'
icon: fas fa-solid fa-feather
order: 2
---

My research interest is **Robotics**. 
My recent research is on Task and Motion Planning for Mobile Manipulators.


## Mobile Manipulator Task Sequencing
* Applications: tasks involving multiple targets distributed in a larger workspace 
* Problem: find the minimum number of base poses and the optimal sequence to visit all targets
* Solution: two-step approach:
1. Task-space clustering: based on kinematic reachability analysis, cluster the task space into a minimum set 
of target clusters such that there exists a reachable base pose for each cluster to reach all inside targets.
2. Task sequencing: compute the shortest base sequence, shortest target sequence, then shortest manipulator 
joint sequence to visit all targets.
* Paper: [Task-Space Clustering for Mobile Manipulator Task Sequencing](https://doi.org/10.1109/ICRA48891.2023.10161293) 
(presented at ICRA 2023)
* Video: [youtu.be/Vopupf81hYo](https://youtu.be/Vopupf81hYo)


## Mobile Manipulator Constrained Optimal Trajectory Planning
* Applications: tasks requiring the end-effector to follow a continuous trajectory (time-parametrized path), 
such as Mobile 3D Printing which is being developed at [Singapore Centre for 3D Printing (SC3DP)](https://www.ntu.edu.sg/sc3dp)
* Problem: constrained optimal trajectory planning for the mobile base
* Solution:
1. Based on the required trajectory and constraints, define an admissible base configuration spacetime.
2. Numerically compute the optimal trajectory inside the admissible base configuration spacetime.
* Paper: [Planning Optimal Trajectories for Mobile Manipulators under End-effector Trajectory Continuity 
Constraint](https://arxiv.org/abs/2309.12251) (submitted for ICRA 2024)
* Video: [youtu.be/yyBv3xGClnk](https://youtu.be/yyBv3xGClnk)


## Publications
Full list: [Google Scholar](https://scholar.google.com/citations?user=6V-YHEkAAAAJ&hl=en&inst=8669986779262753491&authuser=3)

2023:
* **Q.-N. Nguyen**, N. Adrian, and Q.-C. Pham, 
"[Task-Space Clustering for Mobile Manipulator Task Sequencing](https://doi.org/10.1109/ICRA48891.2023.10161293)," 
in 2023 International Conference on Robotics and Automation (**ICRA**). 
([Preprint](https://arxiv.org/abs/2305.17345) | [Video](https://youtu.be/Vopupf81hYo))

Under Review:
* **Q.-N. Nguyen** and Q.-C. Pham, 
"[Planning Optimal Trajectories for Mobile Manipulators under End-effector Trajectory Continuity 
Constraint](https://arxiv.org/abs/2309.12251)," 
submitted for ICRA 2024. 
([Preprint](https://arxiv.org/abs/2309.12251) | [Video](https://youtu.be/yyBv3xGClnk))
