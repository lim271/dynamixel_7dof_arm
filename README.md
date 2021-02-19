# manipulator_7dof_dynamixel

## Frame definition
|         | Link length | Joint type |
| :-----: | :---------: | :--------: |
| Link 1  |   0.0440m   |  Revolute  |
| Link 2  |   0.0540m   |  Revolute  |
| Link 3  |   0.1260m   |  Revolute  |
| Link 4  |   0.0540m   |  Revolute  |
| Link 5  |   0.0750m   |  Revolute  |
| Link 6  |   0.0425m   |  Revolute  |
| Link 7  |   0.0625m   |  Revolute  |
| Gripper |   0.0565m   | Prismatic  |

## D-H parameters
|  $i$  | $\alpha_i$ | $a_i$ |  $d_i$  | $\theta_i$ |
| :---: | :--------: | :---: | :-----: | :--------: |
|   1   |  $-\pi/2$  |   0   | 0.0980m | $\theta_1$ |
|   2   |  $\pi/2$   |   0   |    0    | $\theta_2$ |
|   3   |  $-\pi/2$  |   0   |  0.18m  | $\theta_3$ |
|   4   |  $\pi/2$   |   0   | 0.1175m | $\theta_4$ |
|   5   |  $-\pi/2$  |   0   |    0    | $\theta_5$ |
|   6   |  $\pi/2$   |   0   |    0    | $\theta_6$ |
|   7   |     0      |   0   | 0.119m  | $\theta_7$ |