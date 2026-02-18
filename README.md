# Hi, I'm Tannaz Chowdhury

Computer Engineering @ The University of Toronto focused on computer architecture, digital systems, and hardware/software co-design.

I am interested in projects that sit at the intersection of Verilog, Assembly, and systems programming, where software directly interacts with hardware and architectural decisions matter.

---

## What I Care About

- Computer architecture in practice  
- RTL design and FPGA systems  
- Interrupt-driven embedded programming  
- Memory-mapped I/O and low-level control  
- Hardware-aware software design  
- Control systems and real-time behavior  

---

## Tech Stack

**Languages:**  
C, C++, RISC-V Assembly, Verilog, Python, MATLAB, SQL  

**Architecture & Systems Concepts:**  
Finite state machines, synchronous digital design, interrupt systems, memory-mapped I/O, datapath/control separation, real-time control, numerical modeling  

**Platforms & Tools:**  
DE1-SoC (Cyclone V FPGA), Nios V (RISC-V), VGA pipeline, ModelSim, GDB, Linux, Git/GitHub, LTSpice, Arduino  

---

## Selected Hardware & Architecture Projects

### RISC-V Assembly Systems · DE1-SoC

Low-level interrupt-driven systems written entirely in assembly.

- Configured `mstatus`, `mie`, `mtvec`, and `mcause` to implement timer and pushbutton interrupts  
- Designed structured interrupt service routines with correct calling conventions and stack discipline  
- Controlled LEDs and HEX displays through direct memory-mapped I/O  
- Built event-driven systems without busy-wait polling  

Focus: understanding processor control flow, trap handling, and architectural state transitions.

---

### FPGA Digital Systems Labs · Verilog

Structured progression from combinational logic to full finite state machine systems.

- Designed one-hot and binary-encoded FSMs for sequence detection  
- Built synchronous counters using both structural (T flip-flop chains) and behavioral (`Q <= Q + 1`) styles  
- Implemented a Morse-code transmitter using a control FSM + shift register + timing divider  
- Generated human-visible timing from a 50 MHz clock using clock-enable logic  

Focus: disciplined synchronous design, timing correctness, and datapath/control separation.

---

### Lane Runner FPGA/VGA Game · Verilog, C

Real-time obstacle avoidance game implemented directly in hardware.

- Drove a 640×480 VGA display using a custom sprite pipeline and `.mif` ROMs  
- Designed modular Player, Obstacle, and Game FSMs with structured state transitions  
- Implemented collision detection across discrete lanes in hardware  
- Used LEDs and internal signals for real-time debugging on FPGA  

Focus: hardware state machines controlling graphics timing and game logic.

---

### Hydrofoil Active Stabilization · MATLAB, Embedded C

Control system for a human-powered hydrofoil.

- Filtered >10,000 ultrasonic sensor readings for stable altitude measurement  
- Implemented multi-axis PID control in MATLAB and embedded C  
- Integrated control logic with servo actuation and validated system response  

Focus: real-time feedback control and embedded execution.

---

## I enjoy building systems where understanding the architecture is necessary to make the design work.

---

## Connect

**LinkedIn:**  
https://www.linkedin.com/in/tannaz-chowdhury-5365691ba/

Open to opportunities involving computer architecture, FPGA design, embedded systems, and low-level systems programming.
