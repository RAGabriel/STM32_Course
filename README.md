# STM32_Course
Exercises of the STM32 microcontroller course

Exercises list

- M07A03: Set the internal clock to go through pins
  - Configured the internal clock to go through pins PA2(A7) with frequency of 32.768kHz (Low Speed Clock) and PA8(D9) with frequency of 16MHz (High Speed Clock).
- M08A02: Blink LED
  - Configured PB3(Built-in LED) pin as output and toggle your state every half second.
- M08A03: Push Button
  - Configured PA12 pin as input with pull-up, when pressed toggle the state of PB3(Built-in LED).
  - Configured PB0 pin as input with pull-up, when pressed toggle the state of PB3(Built-in LED) 10 times with a delay of half second.
- M08A05: GPIO Interrupt 
  - Configured PA12 as a external interrupt, when pressed toggle the state of PB3(Built-in LED).