# Walking Light Circuit PCB with 10 LEDs

This project details the design of a walking light circuit using 10 LEDs, controlled by a CD4017 decade counter and a 555 timer IC. This simple yet effective circuit can be used for various applications and demonstrations.

## Components Needed
- **CD4017 Decade Counter**
- **555 Timer IC** (in astable mode)
- **10 LEDs** (any color)
- **Current limiting resistors** (typically 220Ω - 1kΩ depending on the LED used)
- **Breadboard or PCB for layout**
- **Power supply** (5V-15V depending on the specifications of the ICs used)

## Circuit Diagram
(Attach circuit diagram here)

## Working Principle
1. The 555 Timer is configured in astable mode to generate a clock pulse. This pulse acts as a clock input to the CD4017.
2. With each clock pulse, the CD4017 counter advances to the next output pin. When it reaches the last pin, it resets to the first pin.
3. Each LED is connected to the output pins of the CD4017, ensuring that only one LED is active at any time, thus creating a 'walking light' effect.

## Assembly Instructions
1. Set up the 555 Timer in astable configuration.
2. Connect the output of the 555 Timer to the clock input of the CD4017.
3. Connect the LEDs to the output pins of the CD4017, ensuring proper orientation (anode to output pin, cathode to ground through a resistor).
4. Power the circuit and observe the walking light effect!

## Tips
- Make sure to calculate the appropriate resistor values to ensure your LEDs operate within safe limits.
- Consider using a prototype board for initial testing before designing the final PCB.

## Conclusion
This walking light circuit is a fun and educational project that demonstrates basic electronics, timing circuits, and the functionality of the CD4017 and 555 Timer. Happy building!