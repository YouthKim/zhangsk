

### PX4 系统架构（机载+飞控）

![PX4 architecture - FC + Companion Computer](https://docs.px4.io/v1.13/assets/img/px4_arch_fc_companion.c430665d.svg)



## PX4飞行堆栈

![PX4 High-Level Flight Stack](https://docs.px4.io/v1.13/assets/img/PX4_High-Level_Flight-Stack.18829d0a.svg)

### 飞控数据流

![img](https://img-blog.csdnimg.cn/584e84ddb0b24a7fa119607a4f71f2d2.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzMzMDMzMDU5,size_16,color_FFFFFF,t_70)



## 多旋翼控制架构

![动力学模型公式](/home/zhangsk/图片/动力学模型公式.png)

![无人机飞行控制框架](/home/zhangsk/图片/无人机飞行控制框架.png)

![MC Controller Diagram](https://docs.px4.io/v1.13/assets/img/mc_control_arch.21116ef0.jpg)

### 角速率控制器

![MC Rate Control Diagram](https://docs.px4.io/v1.13/assets/img/mc_angular_rate_diagram.d3b839d2.jpg)

### 姿态控制器

![MC Angle Control Diagram](https://docs.px4.io/v1.13/assets/img/mc_angle_diagram.90e53599.jpg)

### 速度控制器

![MC Velocity Control Diagram](https://docs.px4.io/v1.13/assets/img/mc_velocity_diagram.26014b48.jpg)

### 位置控制器

![MC Position Control Diagram](https://docs.px4.io/v1.13/assets/img/mc_position_diagram.9f65e045.jpg)

### 位置和速度组合控制器

![MC Position Controller Diagram](https://docs.px4.io/v1.13/assets/img/px4_mc_position_controller_diagram.4769dc90.png)