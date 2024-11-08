Assembly Stopwatch Program
Introduction
This project is an Assembly-language program that implements a digital stopwatch with key functionalities such as start, stop, pause, reset, and split-time recording. It showcases a foundational understanding of low-level programming, hardware control, and Assembly code flow. Developed during my first semester at Swinburne University in Vietnam, this project was a significant learning experience, where I scored 100/100.

Features
Start: Begin timing with the stopwatch.
Pause: Temporarily halt the stopwatch.
Reset: Return the timer to "00:00".
Split Time: Capture intermediate times, supporting up to 5 split times.
End: Conclude the program.
Technical Details
Interrupt Handling: Keypad inputs are managed via interrupts, allowing real-time control over the stopwatch.
Modular Functions: Each function (e.g., start, pause, reset) is handled through distinct subroutines.
Memory Management: Efficient memory addressing and register handling control the display of elapsed and split times.
Flow Control: Uses loops and conditional branching to manage timing and display logic smoothly.
Instructions
Setup
Clone the repository and open mystopwatchprogram.txt in an Assembly-compatible simulator (like ARMlite).
Paste the code into the simulator, assemble it, and ensure no syntax errors.
Running the Program
C - Start the stopwatch
P - Pause the stopwatch
S - Record split time (up to 5 times)
R - Reset the stopwatch to zero
E - End the program
Project Files
COS10004 Assignment 2 Report_ Vu Thanh Nam.pdf: A report explaining the design, architecture, and technical insights of the stopwatch program.
mystopwatchprogram.txt: The Assembly code file for the stopwatch, complete with detailed comments on functionality.
Future Improvements
Enhanced Split-Time Storage: Implementing arrays to store multiple split times for better data management.
Improved Display: Redesigning the digital display for a clearer, user-friendly interface.
Technologies Used
Assembly Language: The core language for implementing stopwatch functionalities.
ARM Architecture: Program designed to run on ARM simulators like ARMlite.
Summary
Completing this project was a rewarding experience that honed my problem-solving and programming skills. It helped me understand Assembly code flow, low-level logic, and the importance of attention to detail. I enjoyed tackling the challenges in designing this program and felt captivated by the problem-solving process, which has strengthened my interest in low-level programming.
