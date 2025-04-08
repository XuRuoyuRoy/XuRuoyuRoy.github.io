+++
title = "Research Experience"
hideAuthor = true
hideDate = true
hideLastMod = true
+++

_2024~2025_ **Whole-Body Model Predictive Control for Magnetic Actuated Robotic Endoscope**, CUHK
{{< figure src="imga/WBC_IPM.png" width="80%" >}}
{{< figure src="imga/WBC_IPM.gif" width="80%" >}}

- To ensure the operation safety, we need to schedule the motion of end-effector and magnetic endoscopy simultaneously. Traditional hierarchical controller cannot achieve this goal.
- We proposed a whole-body optimal control method, in which the endoscopy and manipulator are modeled as an integrated system.
- To increase the computational efficiency, we proposed a partial simplification method and combined the real-time iteration framwork with the MPC.

_2023~2024_ **Confidence-aware catching for the floating-base manipulator subject to disturbance**, during the visit at Maastricht University
{{< figure src="imga/catchu.gif" width="80%" >}}
{{< figure src="imga/catcho.gif" width="80%" >}}

- Proposed a method to realize the collision-free approach before catching and determining the boundary of the target motion based on maximum likelihood estimation.
- Realize the multi-step prediction of the target that performs quasi-random motion in real-time based on the wavelet network. Evaluate the confidence of predictions based on the Bayesian method.
- Catching object that performs stochastic motion by combining the confidence evaluation and whole-body nonlinear programming, taking the confidence and feasibility into catching simultaneously.

_2019~23_ **Design and control of a manipulator-based landing assistance system for USV-UAV systems**, supported by National Natural Science Foundation of China in CUHK-Shenzhen

{{< figure src="imga/illu_catch.png" width="80%" >}}
{{< figure src="imga/catch.gif" width="80%" >}}

- Manipulator controller design for UAV tracking and catching, improving the tracking performance by designing a robust controller based on the Lyapunov method.
- Design model predictive controller based on the joint model with delay estimation and generate reference trajectory based on the wavelet network.
- System modeling, controller verification, and simulation based on Matlab/Simscape; field experiments of the assistance landing system.


_2018~22_ **Design and control of a wave-driven dual-axis solar tracker**, CUHK-Shenzhen
{{< figure src="imga/st_illu.png" width="80%" >}} 
{{< figure src="imga/st.gif" width="80%" >}}

- Feedback system design based on kinematics analysis; dynamics modeling and decoupling for lower computational complexity.
- Wave-driven controller design based on motion prediction; sliding mode observer design for higher robustness; motion planning for lower energy cost.
- Mechanical design and modeling of a solar tracker without actuators; reduce the required base motion for motion driving based on numerical optimization.

_2015~18_ **Design and control of a permanent-magnet spherical motor(PMSM) for conformal printing**, supported by the National High Technology Research and Development Program of China and National Natural Science Foundation of China in HUST

{{< figure src="imga/illu_pmsm.png" width="80%" >}} 
{{< figure src="imga/pmsm.gif" width="80%" >}} 

- Mechanical design and modeling of a three-DoF spherical motor; optimize magnets arrangement to improve the available workload; force analysis and structure optimization based on ANSYS/Workbench.
- Kinematics and dynamics analysis based on  Euler-Lagrange equation; optimal tool path planning.
- Non-singular terminal sliding mode controller design for robust motion control; stability analysis based on Lyapunov theory; PID controller design and parameter tuning.
- Control cabinet design; system implementation based on Labview and CompactRIO.
