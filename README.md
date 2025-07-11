# Digital Clock Based on 59 Seconds & Minutes 

This project is a **digital clock designed using J-K flip-flops** and basic digital logic components, with a unique feature: it **skips the 17th second and 17th minute** making it an authentic design free from copying. Implemented entirely with logic gates and counters, the clock operates in a **24-hour format** and showcases a practical application of synchronous counters, flip-flops, and combinational logic design.

##  Features

- ⏱ Counts time in HH:MM:SS format using:
  - Mod-10 (0–9) counters
  - Mod-6 (0–5) counters
  - Mod-3 (0–2) counters
-  Automatically resets after 23:59:59
- ❌ Skips 17th second and minute (i.e., jumps from 16 to 18)
-  Outputs displayed on 7-segment displays via a custom decoder
-  Designed with basic logic ICs (no microcontrollers)

##  Components Used

- JK Flip-Flop (IC 7476)
- AND, OR, NOT, NAND, XOR Gates (IC 7408, 7432, 7404, 7400, 7486)
- 7-Segment Displays
- Logic constants (Vcc, GND)

##  Learning Outcomes

- Application of synchronous sequential circuit design
- State table, state diagram, and K-map simplification
- Digital implementation of a real-world timekeeping system
- Logic gating to enforce conditional behaviors (e.g. skip 17)

## 📁 Contributors

- **Md. Sorup Rohan** – Roll: 2107018 – Group: A1(09)  
- **Abdullah Al Saif** – Roll: 2107017 – Group: A1(09)  
- **Institution**: Khulna University of Engineering & Technology (KUET)

## License

This project is created for academic purposes and can be used freely for educational use. Please credit the authors when using or modifying the design.
