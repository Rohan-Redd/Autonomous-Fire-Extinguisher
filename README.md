# Autonomous Fire Extinguisher

## Introduction 🔥🤖

Welcome to the Firefighting Robot Control System! This code controls a robot designed to detect and extinguish fires using various sensors and actuators. The robot's movements are based on fire detection, and it's equipped with a servo-controlled water pump for firefighting.

## Hardware Setup 🛠️

- **Servo Motor**: Controls the water pump's angle for precise firefighting.
- **Sensors**: Utilizes infrared sensors (Left, Right, Forward) to detect the fire's location.
- **Motors**: Drives the robot's movements (Left Motor: LM1, LM2; Right Motor: RM1, RM2).
- **Water Pump**: Activates the pump (connected to pin 6) to extinguish the fire.

## How It Works 🤔🔥

1. The robot scans its surroundings using infrared sensors.
2. If a fire is detected straight ahead, the robot moves forward and activates the water pump.
3. If the fire is detected to the left, the robot turns left.
4. If the fire is detected to the right, the robot turns right.

## Usage 🚀

- Upload the code to your Arduino board.
- Assemble the robot with the specified hardware components.
- Run the robot in an environment with a simulated fire source.
- Observe the robot's movements and firefighting actions based on sensor inputs.

## Safety Precautions ⚠️

- Always supervise the robot while it's operational.
- Use caution when dealing with water and electrical components.

## Future Enhancements 🚀🔮

- Implement advanced pathfinding algorithms for more efficient fire detection and extinguishing.
- Integrate remote control and monitoring capabilities for enhanced user interaction.
- Enhance the robot's firefighting mechanism and agility for improved performance.
