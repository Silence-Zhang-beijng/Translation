# UAVCAN 详表和配置Enumeration and Configuration

官网英文原文地址：http://dev.px4.io/uavcan-node-enumeration.html

我们通过点击选择下图中的“Enable UAVCAN”复选框来启用UAVCAN作为默认的电机输出总线。或者，我们可以在QGroundControl的参数编辑器中将参数UAVCAN_ENABLE设置为3。当UAVCAN设置为2时，可以启用CAN总线，使用PWM波控制电机输出。Enable UAVCAN as the default motor output bus by ticking the 'Enable UAVCAN' checkbox as shown below. Alternatively the UAVCAN_ENABLE parameter can be set to '3' in the QGroundControl parameter editor. Set it to '2' to enable CAN, but leave motor outputs on PWM.

打开Use [QGroundControl](../3_Tutorial/ground_control_station.md) 并且切换到 Setup 视图。点击左面的 Power Configuration 选项。点击“start assignment” 按钮。and switch to the Setup view. Select the Power Configuration on the left. Click on the 'start assignment' button.

第一次发出哔声后，将第一个电调（ECS）控制的螺旋桨快速调整到正确的转向。After the first beep, turn the propeller on the first ESC swiftly into the correct turn direction. The ESCs will all beep each time one is enumerated. Repeat this step for all motor controllers in the order as shown on the我们需要根据 [电机顺序图motor map](../7_Airframe/airframes-motor-map.md)的顺序重复以上步骤配置所有的电机控制器。 这一步只需要执行这一次，即使固件升级之后也不用重复以上步骤。This step has to be performed only once and does not need to be repeated after firmware upgrades.

![UAVCAN Enumeration Controls (bottom right of image)](../pictures/logos/uavcan-qgc-setup.png)

