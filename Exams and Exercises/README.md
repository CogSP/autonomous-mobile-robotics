# Midterm 2022-2023

- Problem 1: single-legged hopping robot
	(a) geometry of the configuration space
	(b) kinematic model of the robot with physical interpretation
		- you may choose a basis for which the physical interpretation of $u_i$ is not clear
	(c) TODO
	(d) TODO
	(e) TODO

- Problem 2: TODO

- Problem 3: TODO


# Midterm 2021-2022

- Problem 1: point $q = (x, y, z)$ constrained to move over a sphere surface
	(a) GC and KC
	(b) Local and Global mobility
	(c) KM and controllability

- Problem 2: TODO

- Problem 3: TODO




# Textbook Exercises
- 11.1: RWD tricycle connected to N trailers with revolute joints
	- find a set of generalized coordinates
- 11.2: Omnidirectional Mecanum wheels robot and its Pfaffian constraints
	- prove that the constraints are partially integrable and that the orientation of the vehicle is a linear function of the wheel rotation angles
	- MATLAB code provided
- 11.3: Show the involutivity of the distribution $\Delta = span{g_1, …, g_{n-1}}$ for a kinematic model with a single kinematic constraint
- 11.4: Prove that a set of Pfaffian constraints that doesn't depend on the generalized coordinates $q$ is always integrable and so is not controllable
	- the explanation is written in a textbox in the solutions pdf
- 11.5: TODO
- 11.6: TODO
- 11.7: TODO
- 11.8: TODO
- 11.9: TODO
- 12.1: Configuration space of a 6 DoF robot mounted on a unicycle
	- keep in mind that even in $\mathbb{R}^3$ a rotation in $SO(2)$ (see 2. Configuration Space)
- 12.2: Modify configuration space distance for a 2R manipulator so that the posture doesn't change if $q_1$ and $q_2$ are increased (or decreased) by a multiple of $2\pi$
	- the important thing for this new distance is that its value is the same (since it's posture is the same) if you sum or decrease a multiple of $2\pi$ from a coordinate. It's not needed that this new distance has the same values of the previous one (although it has the same values if the Euclidean distance between $q_1$ and $q_2$ is not larger than $sqrt(2)\pi$)