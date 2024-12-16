# Accident-prevention-system-using-Eye-Blink-and-Alcohol-detector

## Overview
This project aims to enhance road safety by developing an accident prevention system using real-time monitoring of eye blinks and alcohol levels. The system utilizes sensors and microcontroller-based processing to detect signs of driver fatigue or intoxication and takes necessary preventive actions, ensuring safer driving conditions.

## Features
- **Eye Blink Detection:** Detects driver fatigue or drowsiness by monitoring eye-blink frequency using an IR sensor.
- **Alcohol Detection:** Measures alcohol levels using an MQ3 sensor to identify driver intoxication.
- **Buzzer Alert:** Triggers a warning alarm to alert the driver or passengers if unsafe conditions are detected.
- **Vehicle Control:** Deactivates the vehicle's ignition system to prevent accidents in extreme conditions (e.g., alcohol detection).

## Components
### Hardware
- **Arduino UNO**: Microcontroller for processing sensor data.
- **Eye Blink Sensor (IR Sensor)**: Detects eye blinks to monitor driver fatigue.
- **Alcohol Sensor (MQ3)**: Measures alcohol concentration in the air.
- **Buzzer**: Provides an audible alert for safety warnings.
- **Relay Module**: Controls the ignition system.
- **12V Battery**: Provides power to the system.
- **Connecting Wires and Resistors**: For circuit connections.

### Software
- **Arduino IDE**: For programming and uploading code to the Arduino board.
- **Embedded C/C++ Code**: Used for system logic and sensor integration.

## Hardware Setup
1. Connect the eye blink sensor to the Arduino UNO:
   - VCC to 5V
   - GND to GND
   - Signal pin to an analog input pin (e.g., A0)
2. Connect the MQ3 alcohol sensor:
   - VCC to 5V
   - GND to GND
   - Signal pin to another analog input pin (e.g., A1)
3. Connect the buzzer to a digital output pin (e.g., D9).
4. Use a relay module to control the ignition system:
   - VCC to 5V
   - GND to GND
   - Signal pin to a digital output pin (e.g., D10).
5. Power the Arduino using the 12V battery.


## Usage
1. Power on the system.
2. The sensors continuously monitor the driver's condition:
   - **Eye Blink Sensor:** Tracks eye blinks and detects signs of drowsiness.
   - **Alcohol Sensor:** Monitors the alcohol concentration in the driver's breath.
3. If an unsafe condition is detected:
   - The buzzer will sound an alert.
   - In the case of high alcohol levels, the relay will deactivate the vehicle's ignition system.

## Circuit Diagram
![System](https://github.com/user-attachments/assets/4a9f6173-f7b4-426e-96f6-c3a2762ec439)

## Applications
- Preventing road accidents caused by driver fatigue or alcohol consumption.
- Ensuring compliance with safety standards in commercial vehicles.
- Enhancing safety in personal vehicles.

## Future Enhancements
- Integration with GPS to alert authorities in case of emergency.
- Real-time monitoring via a mobile app.
- Improved sensors for higher accuracy and reliability.

## Contributing
Contributions are welcome! If you have suggestions for improvements or new features, feel free to create a pull request or raise an issue.

## Acknowledgements
- Inspired by the need to enhance road safety.
- Special thanks to open-source communities for their resources and tools.

## Methodology:

![Flowchart](https://github.com/user-attachments/assets/8f82427d-eb61-403e-803e-4a1e2939293b)

## Alcohol Detection:

![Alcohol_detected](https://github.com/user-attachments/assets/506af8f3-2050-48a3-92bc-1d4e8f0e7c53)
