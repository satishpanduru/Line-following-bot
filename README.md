#Self Driving Vehicle

Components Used:

1.Arduino Uno: Microcontroller for processing inputs and controlling outputs.

2.Ultrasonic Sensors: For detecting and measuring the distance to obstacles.

3.IR Sensors: For line detection and following.

4.Motor Drivers: To control the speed and direction of the motors.

5.DC Motors: For driving the wheels of the bot.

6.Chassis: Framework to house all components.





Implementation Process:

1.Assembly: Mounted the ultrasonic and IR sensors on the chassis along with the DC motors and connected them to the Arduino through the motor driver.

2.Programming: Developed Arduino code to read sensor inputs and make real-time decisions for movement. The IR sensors detect the line on the ground, while the ultrasonic sensors measure the distance to obstacles.

3.Line Following: Programmed the bot to follow a designated path by continuously adjusting its direction based on IR sensor inputs.

4.Obstacle Avoidance: Implemented an algorithm to stop or change direction when obstacles are detected by the ultrasonic sensors.

5.Testing and Optimization: Iteratively tested the bot's performance and fine-tuned the code to ensure accurate and reliable operation.
