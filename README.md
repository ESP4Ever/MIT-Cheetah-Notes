# MIT-Cheetah-Note
## MIT Cheetah simulation platform source code notes and some third-party components
### Warehouse description
>The notes I made while reading the source code of the MIT Cheetah simulation platform are organized manually. In order to better understand the source code, I have manually organized some reference papers mentioned in the corresponding code. I hope to communicate with my peers. You are welcome to correct any errors in the notes.

### File structure
The `ref` folder stores pdf files of relevant papers and e-books.
`BalanceController` corresponds to the analysis of the BalanceController-related files in the source code, mainly calling the qpOASES solver to complete the optimization solution process of the quadruped robot GRF.
`Quadruped` corresponds to the analysis of the Quadruped-related files in the source code, mainly to build the dynamics and kinematics model of the quadruped robot.
`LegController` corresponds to the analysis of the LegController-related files in the source code, mainly the parameter processing of the quadruped robot leg kinematics and the calculation of forward and inverse kinematics.
`FootSwingTrajectory` corresponds to the analysis of FootSwingTrajectory related files in the source code, mainly planning the foot position, velocity and acceleration of the swinging leg through cubic Bezier curve interpolation.
`convexMPC_interface` corresponds to the analysis of convexMPC_interface related files in the source code, mainly providing an interface for solving MPC problems and assigning parameters.
`RobotState` corresponds to the analysis of RobotState related files in the source code, mainly providing an object for storing robot state information and printing state information.
`SolverMPC` corresponds to the analysis of SolverMPC related files in the source code, mainly building an MPC problem and solving it.
`Gait` corresponds to the analysis of Gait related files in the source code, mainly analyzing the robot's walking gait, involving the analysis of the swing phase and the support phase.
`ConvexMPCLocomotion` corresponds to the analysis of ConvexMPCLocomotion related files in the source code, mainly combining the control of gait with the MPC controller.
`PositionVelocityEstimator` corresponds to the analysis of the PositionVelocityEstimator related files in the source code, mainly to build a linear Kalman filter to complete the estimation of the body position and velocity.
The `WBC` directory stores the analysis of all WBC-related files in the source code.

### Others
Original project address: [https://github.com/mit-biomimetics/Cheetah-Software](https://github.com/mit-biomimetics/Cheetah-Software)
qpOASES solver address: [https://github.com/coin-or/qpOASES](https://github.com/coin-or/qpOASES)

## Loading......
