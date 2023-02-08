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
- M09A01: General Purpose Timer
  - Configured TIMER15 in counter mode UP, counting to 2000 in 2 seconds.
- M09A02: Timer Blink LED
  - Configured TIMER6 (basic timer) in counter mode UP, counting to 250 in 0.25 seconds and toggle the state of PB3(Built-in LED).
- M09A03: Delay Function with Timer
  - Configured TIMER16 (general purpose) in counter mode UP with a refresh rate of 1 milisecond. In ***main*** was created a private function to make a delay in miliseconds.
