# Autonomous 4WD Robotic Car
**Contributors:** Momina Haq, Abdul Manan 
**Description:** This project involves the design, construction, and programming of an autonomous four-wheel drive robotic car integrating mechanical design, electronics, and software algorithms. The car navigates its environment, detects obstacles using an ultrasonic sensor (HC-SR04), and autonomously avoids collisions. It uses an Arduino Uno R3 as the main controller, an L293D motor driver for four DC motors, and three rechargeable Lithium-ion batteries (LL 18650-1800mAh, 3.7V). The project demonstrates the integration of hardware and software systems for intelligent autonomous movement.
## Working Principle
The car moves forward while continuously measuring distance to obstacles. If an obstacle is detected within 2 cm, the car stops, reverses, and resumes forward movement. The Arduino processes sensor data and controls the motors independently through the L293D motor driver. A four-motor system allows each wheel to operate individually for better traction and maneuverability. Obstacle avoidance is achieved using a programmed algorithm in the Arduino.
## Physics Principles
- Forces: Dynamics and equilibrium, traction, friction, drag, and weight.  
- Momentum: F = mv/t; change in momentum determines applied force.  
- Energy Conversion: Electrical energy from batteries is converted to mechanical energy via the motors, with some loss as heat.
## Components
- Motor System: Four DC motors with L293D motor driver shields using H-bridge configuration for bidirectional control.  
- Arduino Uno R3: Programmed using Arduino IDE, interfaces with motors and ultrasonic sensors.  
- Ultrasonic Sensor (HC-SR04): Measures distance using ultrasonic pulses; connected via TRIG and ECHO pins.  
- Batteries: Three rechargeable Lithium-ion batteries (3.7V, 1800mAh).  
- Jumpers: Male-to-female and female-to-female jumpers for sensor, Arduino, and motor connections.  
- Chassis: Compact, lightweight design (23.5 cm x 16.6 cm) with cutouts for wheels (6.5 cm diameter).  
- Datum Pointer: Used as reference for sensor calibration and consistent readings.
## Assembly & Manufacturing
1. Chassis Assembly: Cut and assemble base, mount motors and wheels.  
2. Electronics Setup: Connect Arduino, motor driver, sensors, and batteries using jumpers.  
3. Wiring: Ensure each motor connects to a separate motor output.  
4. Power Supply: Connect batteries to motor driver input.  
5. Programming: Upload Arduino code for obstacle avoidance and motor control.  
6. Testing: Verify movement, obstacle detection, and algorithm performance.
## Cost Analysis
| Component           | Cost (PKR) |
|-------------------|-----------|
| Batteries (3)      | 960       |
| Jumpers            | 240       |
| Arduino Uno R3     | 1880      |
| Ultrasonic Sensor  | 200       |
| Motors (4)         | 360       |
| Motor Driver       | 400       |
| Wheels (4)         | 400       |
| Datum Pointer      | 100       |
## Strengths
- Fully autonomous operation.  
- Modular and scalable design for additional features.  
- Efficient 4-motor independent drive system.
## Weaknesses
- Limited terrain adaptability.  
- Battery life constraints.  
- Ultrasonic sensor range and interference limitations.
## Conclusion
This project demonstrates the feasibility of building a low-cost autonomous robotic car integrating mechanical, electrical, and software engineering principles. It can navigate environments, detect obstacles, and perform autonomous maneuvers with potential for further enhancements in real-world applications.
