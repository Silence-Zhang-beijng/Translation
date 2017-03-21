# UAVCAN 详表和配置Enumeration and Configuration

官网英文原文地址：http://dev.px4.io/uavcan-node-enumeration.html

我们通过点击选择下图中的“Enable UAVCAN”复选框来启用UAVCAN作为默认的电机输出总线。或者，我们可以在QGroundControl的参数编辑器中将参数UAVCAN_ENABLE设置为3。当UAVCAN设置为2时，可以启用CAN总线，使用PWM波控制电机输出。

打开Use [QGroundControl](../3_Tutorial/ground_control_station.md) 并且切换到 Setup 视图。点击左面的 Power Configuration 选项。点击“start assignment” 按钮。

第一次发出哔声后，将第一个电调（ECS）控制的螺旋桨快速调整到正确的转向。The ESCs will all beep each time one is enumerated. 我们需要根据 [电机顺序图](../7_Airframe/airframes-motor-map.md)的顺序重复以上步骤配置所有的电机控制器。 这一步只需要执行这一次，即使固件升级之后也不用重复以上步骤。

![UAVCAN Enumeration Controls (bottom right of image)](../pictures/logos/uavcan-qgc-setup.png)

