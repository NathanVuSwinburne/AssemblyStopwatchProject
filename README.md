# Project Title: Assembly Stopwatch Program

## Introduction
This project is an Assembly-language program that implements a digital stopwatch with functionalities like start, stop, pause, reset, and split-time recording. Developed as part of my coursework at Swinburne University in Vietnam, this project demonstrates foundational skills in low-level programming, problem-solving, and control of timing operations. I achieved a perfect score of 100/100 on this assignment.

## Features
- **Start**: Begin timing with the stopwatch.
- **Pause**: Temporarily halt the stopwatch.
- **Reset**: Return the timer to "00:00".
- **Split Time**: Capture intermediate times, supporting up to 5 split times.
- **End**: Conclude the program.

### Technical Details
- **Interrupt Handling**: Manages keypad inputs for real-time control.
- **Modular Functions**: Separate subroutines for start, pause, reset, and other actions.
- **Memory Management**: Uses precise memory addressing for display.
- **Flow Control**: Loops and conditional branching ensure smooth operations.

## Instructions
### Setup
1. Clone the repository.
2. Open `mystopwatchprogram.txt` in an Assembly-compatible simulator (e.g., [ARMlite](https://peterhigginson.co.uk/ARMlite/)).
3. Copy and paste the code into the simulator, assemble it, and check for errors.

### Running the Program
- **C** - Start the stopwatch
- **P** - Pause the stopwatch
- **S** - Record split time (up to 5 times)
- **R** - Reset the stopwatch to zero
- **E** - End the program

### Project Files
- **`COS10004 Assignment 2 Report_ Vu Thanh Nam.pdf`**: Detailed report on the design and implementation.
- **`mystopwatchprogram.txt`**: Assembly code file, fully commented for clarity.

## Future Improvements
- **Enhanced Split-Time Storage**: Implement arrays to manage multiple split times.
- **Improved Display**: Redesign for clearer, user-friendly interaction.

## Technologies Used
- **Assembly Language**: For implementing stopwatch functionalities.
- **ARM Architecture**: Compatible with ARM simulators like ARMlite.

## Summary
Completing this project strengthened my skills in low-level programming and problem-solving. It was an enjoyable and educational experience, helping me gain a deeper understanding of Assembly code flow and timing logic. I found the process of solving complex problems in Assembly to be both challenging and rewarding.
