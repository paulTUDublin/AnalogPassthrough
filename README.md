# AnalogPassthrough

The project included here is the basic operation of the analog-to-digital converter (ADC) and digital-to-analog converted (DAC) on the STM32L432KC. 
Helper functions have been provided that handle the configuration of the pin modes (`pinMode()`), initialisation of the ADC (`initADC()`), initialisation of the DAC (`initDAC()`), reading of the ADC (`readADC()`), and writing to the DAC (`writeDAC()`). 
Please ensure you reveiw these function before uplaoding the code to your board.
This builds upon the work in [AnalogIn](https://github.com/paulTUDublin/AnalogIn) and [AnalogInPWMOut](https://github.com/paulTUDublin/AnalogInPWMOut) and uses the analog input value to read the input voltage and update the DAC output on **PA4**.

# Studio task/activity #3

Advanced ADC: include DAC to modulate some output e.g. LED and sine wave pass through

- [X] Copy or clone this [repository](https://github.com/paulTUDublin/AnalogPassthrough){target="_blank"} and open as a platformIO project.
- [ ] Verify the board is working as you alter the voltage at the input pin using the potentiometer on the board. You will need to add an LED and current-limiting resistor to **PA4**.
- [ ] Configure the function generator output to be a sinewave with an amplitude of 1.5 V and an offset of +1.5 V.
- [ ] Replace the input from potentiometer with a supply from the function generator and use the oscilloscope to view the voltage at the DAC output pin. Is the pass through working correctly?
- [ ] How would you demonstrate the effect of sample-and-hold (S/H) and quantisation?
- [ ] Document any progress/changes in the README.md file (use [Markdown](https://www.markdownguide.org/cheat-sheet/){target="_blank"} to format this document.) and upload your project to your GitHub repo.
