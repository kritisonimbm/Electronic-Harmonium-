#  Touch-Based Electronic Harmonium Using 555 Timer IC

##  Project Overview
This project is a **electronic harmonium** designed using a **555 timer IC** and a **resistor network**.
Instead of mechanical keys, copper pads on a custom PCB are played using a metal probe. When the probe touches a pad, a corresponding musical note is produced through a speaker.

The project is completely **hardware-based** and does **not use any microcontroller or programming language**.

---

## Musical Notes
The harmonium generates the following Indian classical notes:

**SA – RE – GA – MA – PA – DHA – NI – SA (Higher Octave)**

Each note is produced by a specific resistor value connected in the 555 timer circuit.

---

##  Components Used
- NE555 Timer IC  
- Resistors (different values for different notes)  
- Capacitor (timing capacitor)  
- 8Ω Speaker  
- 9V Battery  
- Custom etched PCB with copper touch pads  
- Connecting wires  

---

##  Working Principle
- The **555 timer IC** is configured in **astable mode** to generate a square wave.
- Each touch pad connects a different resistor into the timing network.
- Touching a pad completes the circuit using finger conductivity.
- The resistance value changes the oscillation frequency.
- The speaker converts this frequency into an audible musical note.

### Frequency Equation
f = 1.44 / ((R1 + 2R2) × C)

Where:
- `R2` changes with each touch pad  
- `C` remains constant  
- `f` determines the musical note  

---

##  PCB Description
- Linear copper touch pads arranged like harmonium keys
- Notes labeled directly on the PCB
- 555 timer IC and passive components mounted on the board
- Battery and speaker connected externally

---

## How to Use
1. Connect the 9V battery to the PCB.
2. Connect the speaker to the output terminals.
3. Touch any copper pad using your finger.
4. The corresponding musical note will be heard.
5. Release the pad to stop the sound.

---

## Code / Programming
This project is **purely hardware-based** and does **not require any programming code**.

There is:
- No microcontroller  
- No firmware  
- No Arduino / Python / C code  

Sound generation is achieved entirely using **analog electronics**.

---

## Advantages
- Simple circuit design  
- Low-cost implementation  
- No software dependency  
- Easy to demonstrate and understand  

---

##  Limitations
- Square wave output (basic sound quality)
- No volume control
- Only one note can be played at a time
---

## Applications
- Educational electronics project  
- College mini project  
- Demonstration of 555 timer IC applications  
- Basic musical electronics  

---



## 👩‍💻 Author
**Kriti Soni**  
B.E. Electronics & Communication Engineering  
MBM University, Jodhpur
