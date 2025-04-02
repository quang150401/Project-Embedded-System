## How it works?

The circuit uses an ESP32 as the central microcontroller to control a MAX7219 LED matrix for displaying dice roll results and a buzzer for sound output when the user presses a button.  

- When the button is pressed, the ESP32 receives a signal from GPIO14, generates a random number between 1 and 6, and sends the corresponding data to the MAX7219 to display the result.  
- The buzzer (connected to GPIO25) will emit a sound each time the dice is rolled.  
- The circuit is powered via USB-C, then stepped down to 3.3V using an AMS1117 regulator to supply power to the ESP32.  

📌 **Conclusion:** When the user presses the button, the circuit generates a random number and displays the result on the LED matrix with an accompanying sound signal.
