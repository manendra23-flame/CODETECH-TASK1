Name: YADAV MANENDRAKUMAR VINODKUMAR                         <br>
Company: CODTECH IT SOLUTIONS                                 <br>
ID: CTO8DS3773                                                 <br>
Domain: Embedded Systems                                        <br>
Duration: July to April 2024                                     <br>
Mentor: Neela Santosh Kumar                                       <br>


Project Overview: LED toggle (LED Fading Effect)
Objective:
The goal of this project is to create a visual effect using two LEDs where they alternately fade in and out, creating a pleasing visual effect. This is achieved by varying the brightness of each LED using PWM (Pulse Width Modulation) control provided by Arduino.

Components Used:

Arduino board (e.g., Arduino Uno)
Two LEDs
Resistors (appropriate values for LEDs, typically 220 ohms to limit current)
Breadboard and jumper wires for circuit connections
Code Explanation:

Initialization (setup() function):

The code begins by setting up two digital pins (LED1 on pin 3 and LED2 on pin 5) as outputs using pinMode() function.
Main Program Loop (loop() function):

First for loop:

This loop gradually increases the brightness of LED1 from off (brightness 0) to full brightness (brightness 255).
Simultaneously, it decreases the brightness of LED2 from full brightness (brightness 255) to off (brightness 0).
This creates a fading effect where LED1 appears to fade in while LED2 fades out.
Second for loop:

After the first loop completes, this loop reverses the fading effect:
It decreases the brightness of LED1 from full brightness (255) back to off (0).
It increases the brightness of LED2 from off (0) back to full brightness (255).
This reversal creates the effect where LED1 now fades out while LED2 fades in.
Delay (delay(30)):

A short delay of 30 milliseconds is added after each change in brightness. This delay is crucial as it smooths out the transition between different brightness levels, making the fading effect visually smoother.
Repeat:

After completing both loops (one fading in while the other fades out, and vice versa), the loop() function repeats indefinitely.
This creates a continuous cycle of fading effects, giving the appearance that the LEDs are continuously fading in and out in an alternating pattern.
Conclusion:
This project is a simple yet effective demonstration of PWM control on Arduino to create a fading effect with LEDs. It utilizes basic programming constructs (for loops and analogWrite() function for PWM) and is suitable for beginners to understand how to control LEDs for visual effects using Arduino. The fading effect achieved adds an aesthetic appeal to the LEDs, making it a popular introductory project in Arduino-based electronics.

output (simulation on tinkercad):

![IMG_20240703_180353_477](https://github.com/manendra23-flame/CODETECH-TASK1/assets/174607434/ca17b8aa-d8e8-48ef-bc36-4c858b319e51)

