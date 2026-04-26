Dynamic LED Timer with Potentiometer Control
 
Project Description
This project combines a countdown timer with adjustable LED blinking speed and a pause functionality, all controlled using a potentiometer. It’s a simple yet powerful Arduino-based system that demonstrates real-time input control and timing behavior.
Features
Countdown timer functionality
LED blinking with adjustable speed
Potentiometer-based control
Pause/Resume feature using threshold value
Optional LCD/Serial Monitor output
Hardware Requirements
Arduino board (e.g., Arduino Uno)

LED
Resistor (220Ω recommended)
Potentiometer (10kΩ)
Breadboard
Jumper wires
(Optional) LCD Display (16x2)

Dependencies
If you are using an LCD display, install:
LiquidCrystal Library
Installation Steps:
Open Arduino IDE
Go to Sketch → Include Library → Manage Libraries
Search for LiquidCrystal
Click Install

Circuit Connections
LED → Digital Pin (e.g., Pin 13) via resistor
Potentiometer:
One side → 5V
Other side → GND
Middle pin → Analog Pin (e.g., A0)
LCD (optional) → Connect as per standard LiquidCrystal wiring

How to Run the Project
Connect all components to your Arduino board
Open Dynamic-LED-Timer.ino in Arduino IDE
Select correct board and port
Upload the code
Use the potentiometer to:
Adjust LED blinking speed
Trigger pause condition (based on threshold)

Observe:
Countdown timer output
LED blinking behavior

Troubleshooting
❌ LED not blinking → Check wiring and resistor
❌ No Serial output → Ensure correct baud rate (9600)
❌ Potentiometer not working → Verify analog pin connection
❌ LCD not displaying → Check contrast and wiring

Future Improvements
Add buzzer for alert
Use OLED display
Add button controls
Save timer settings in EEPROM
