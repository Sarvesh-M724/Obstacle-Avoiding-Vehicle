# Obstacle-Avoiding-Vehicle
ObjectiveDesigned and implemented a self-navigating robotic vehicle capable of real-time obstacle detection and path correction using ultrasonic sensing and PWM-based motor control.

Technical Evidence:
Sensor Fusion: Integrated an HC-SR04 Ultrasonic Sensor with a servo-mounted scanning mechanism to map a 180° field of vision.
Navigation Logic: Developed an interrupt-driven algorithm in Embedded C that calculates distance thresholds and triggers steering maneuvers to avoid collisions.Motor Control: Utilized an L298N Dual H-Bridge driver to manage differential steering and speed regulation.
Validation: View the images/ folder for the full system schematic and a demo video of the vehicle navigating a complex "maze" environment.Hardware StackMicrocontroller: Arduino Uno (ATmega328P) Sensors: HC-SR04 Ultrasonic Sensor Actuators: DC Gear Motors + SG90 Servo Power: 7.4V Li-ion Battery configuration
