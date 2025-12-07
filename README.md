# One Counter Timer
## Description

A single-digit counter timer using a 555 timer IC and 74LS390 counter IC, displayed on a 7-segment display. The counter increments from 0 to 9 repeatedly at a fixed interval.

## Components

* 555 Timer IC (Astable mode)
* 74LS390 4-bit Binary Counter IC
* 7-Segment Display
* Resistors & Capacitors
* Optional pushbutton for manual reset

## How It Works

1. The 555 timer generates clock pulses at a fixed frequency.
2. The 74LS390 counter IC increments its count on each pulse.
3. The count is displayed on the 7-segment display using a BCD-to-7-segment decoder.
4. Optional pushbutton allows manual reset of the counter to 0.

## Learning Outcomes

* Understanding digital counters
* Designing timing circuits with a 555 timer
* Displaying binary counts on a 7-segment display
* Using Multisim for circuit simulation
* 
