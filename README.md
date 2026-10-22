# Hi, I'm Dre Clark 👋

**Electrical Engineering Technology (EET) Student @ Purdue University Fort Wayne**  
*GPA: 3.96 (Dean's List & Honors List) | Expected Graduation: May 2029*  
*Focus Areas: Hardware Validation, Embedded Systems, Digital Logic Design, and Rapid Prototyping.*

---

## Technical Skill Stack

| Category | Competencies & Tools |
| :--- | :--- |
| **Circuit Design & Logic** | Digital Logic Design, Sequential State Machines, Circuit Analysis (AC/DC), VHDL, NI Multisim, Quartus II |
| **Embedded & Microcontrollers** | Arduino Uno (C++ / C), Register-Level GPIO, 7400-Series TTL ICs, FPGA Development Boards, PWM Signaling |
| **CAD & Fabrication** | Autodesk Inventor (Parametric Modeling & Assemblies), FDM 3D Printing (Ultimaker Cura, TPU/PLA Slicing), Soldering, Breadboarding |
| **Lab Equipment & Testing** | Digital Multimeters (DMM), Oscilloscopes, Function Generators, Digital Logic Probes, Hardware-in-the-Loop (HIL) |
| **Software & Scripting** | Python (CLI Apps, File I/O), C/C++, Git / GitHub, Markdown |

---

## 📌 Featured Engineering Projects

### 🦾 [Bio-Mimetic Prosthetic Hand](https://github.com/DreClark-EET/prosthetic-hand-series)
> **Tech Stack:** *Autodesk Inventor, Ultimaker Cura, Arduino Uno, C++, SG90 / MG996R Servos, Tendon Actuation*  
- **Overview:** Leading an ongoing 5-stage R&D pipeline to transform a low-cost mechanical proof-of-concept into a self-powered medical device prototype.
- **Parametric CAD Design:** Modeled human finger joint constraints in Autodesk Inventor to optimize range of motion, assembly clearances, and bio-mimetic pre-curves to prevent joint binding.
- **Embedded Firmware:** Programmed Arduino microcontrollers in C++, utilizing internal `INPUT_PULLUP` configurations to eliminate floating pin state errors and cleanly process button matrix logic.
- **Mechanical Innovation:** Decoupled wrist rotation from finger tension by engineering a centralized through-hole routing manifold concentric with the wrist axis.
- **Current Development:** Transitioning to high-torque metal-geared MG996R servos, braided tensile lines, and planning future analog EMG sensor integration.

### 🚥 [Digital Drag-Race Timing System](https://github.com/DreClark-EET/drag-race-timing-system)
> **Tech Stack:** *Digital Logic, NI Multisim, 7476 JK Flip-Flops, 7493 Counters, 7447 BCD Decoders, 555 Timer IC, 7400 TTL Gates*  
- **Overview:** Designed, simulated, and physically breadboarded a complete digital logic timing circuit replicating a drag strip's sequential "Christmas Tree" light and timer system.
- **Clock Generation & State Control:** Configured a 555 timer IC in astable mode for a precise 10Hz square-wave clock, driving a synchronous state machine via 7476 JK flip-flops for the Red-Yellow-Green sequence.
- **Logic Interlocks & Counters:** Implemented an AND-gate logic matrix (74LS08) as a safety interlock to hold binary counters at zero until the final green light state, feeding 7493 counters and 7447 drivers for dual 7-segment display output.
- **System Debugging & Validation:** Utilized digital logic probes to troubleshoot node placement on reset capacitors and isolate internal gate damage in 7400-series IC packages during physical breadboarding.

---

## 📅 Upcoming Engineering Projects

### 🎧 CMoy High-Performance Analog Headphone Amplifier
> **Tech Stack:** *KiCad, NE5532 Op-Amps, TLE2426 Rail Splitter, PCB Design & Analog Circuitry*
- Capturing a custom schematic in KiCad for a portable 9V-powered analog headphone amplifier engineered to drive 32Ω low-impedance headphones cleanly.
- Features dual NE5532 op-amp gain stages (~5.5x voltage gain), 1.0µF DC-blocking input capacitors, and a TLE2426 active rail-splitter delivering a stable +4.5V virtual ground.
- Optimized with a 10Ω ground isolation resistor and dual 220µF power-rail capacitors to handle heavy bass transients without voltage sag or clipping prior to custom PCB track layout.

---

## 💼 Upcoming Experience

- **Incoming EET Academic Tutor & Digital Circuits Lab Assistant** | *Purdue University Fort Wayne* (Starting January 2027)
  * Selected by faculty to mentor undergraduate students in core Electrical Engineering Technology coursework through one-on-one and group tutoring sessions.
  * Guide students through digital circuits lab experiments, breadboard assembly, logic gate testing, VHDL debugging, and oscilloscope measurements.
  * Reinforce fundamental AC/DC circuit analysis, digital logic design, and hardware troubleshooting to improve student concept mastery and academic success.
