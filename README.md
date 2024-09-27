# Turn-Signal-System-Simulation-for-a-Car-PIC16F877A

This turn signal system is designed to control the indicators of a vehicle using a microcontroller. It utilizes LED lights to represent left and right turn signals, allowing for clear communication of directional intentions to other drivers. The system incorporates a button interface to activate or deactivate the signals, and it features a blinking functionality that adheres to standard signaling protocols. The microcontroller continuously monitors the button states and manages the timing of the LED blinks to ensure visibility and safety on the road.

## Features
- Microcontroller interface for controlling LEDs based on input from PORTA.
- LED control based on switch-case logic for different input states (0-6).
- Macro function to handle specific LED blinking patterns.
- Infinite loop for continuous input monitoring.

## Code Explanation
- **Initialization**: Sets up ADC and interrupt settings.
- **LED Control**: Turns on or blinks LEDs based on input.
- **Delay Handling**: Uses `delay_ms()` for visual confirmation of state changes.

## Usage
1. Connect LEDs to PORTB of the microcontroller.
2. Input values can be provided to PORTA.
3. The program will react according to the defined logic.

## User Interface Examples

<p align="center">
    <img width="741" alt="zmg1" src="https://github.com/user-attachments/assets/9b3751e5-cfb1-40fc-9c37-613d0df45760">
    <br>
    Figure 1: Display when blinking left (Simulation of the front and rear turn signals on the car left)
</p>

<br><br>

<p align="center">
    <img width="741" alt="zmg2" src="https://github.com/user-attachments/assets/62cb4f95-c244-4ed2-a971-b79c7d0b4b72">
    <br>
    Figure 2: Display when we want to activate all four turn signals (Simulation)
</p>

<br>

## 🧰 Languages & Tools 

<div style="display: inline;">
    <img src="https://skillicons.dev/icons?i=cpp"style="margin-right: 10px;" />
    <img src="https://github.com/user-attachments/assets/f29a2b13-cfc7-4e15-a0b6-1180dc7ba9ca" width="70" height="70"  &nbsp; &nbsp; >
    <img src="https://github.com/user-attachments/assets/cf1d8532-3d73-4eed-9139-c02b9aa10ddb" width="65" height="65" &nbsp; &nbsp;/>
    <img src="https://github.com/user-attachments/assets/906cc158-0e38-420f-b0b4-64fc227677e7" width="65" height="65" &nbsp; &nbsp;/>

</div>
