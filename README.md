# Wien Bridge Oscillator - Electronic Engineering Practice Project
## 📖 Project Overview

This project designs and implements a classic **Wien Bridge Oscillator**, an analog circuit capable of generating stable sine wave output. Invented by German physicist Max Wien in 1891, this circuit is a classic design in electronic engineering.

### Project Features

- 🎯 **Classic Design**: Sine wave oscillator using operational amplifier and RC network
- 📊 **Frequency Stable**: Oscillation frequency precisely determined by RC network
- 🔧 **Amplitude Stable**: Includes diode limiting circuit to prevent clipping distortion
- 💻 **Open Source Simulation**: Designed and verified using Falstad Circuit Simulator
- 📝 **Complete Documentation**: Includes both Chinese and English project documentation, suitable for applications

### Project Showcase

![wienbridge_circuit](assets/wienbridge_circuit.gif)

---

## 🔬 Technical Principles

### Wien Bridge Oscillator Working Principle

The Wien Bridge Oscillator uses an RC series-parallel network to provide positive feedback, combined with an operational amplifier to form an oscillation loop.

#### Oscillation Conditions (Barkhausen Criterion)

1. **Loop Gain ≥ 1**: Compensates for circuit losses to maintain oscillation
2. **Phase Shift = 0°**: Ensures positive feedback

#### Frequency Calculation Formula

```
f = 1 / (2πRC)
```

In this design:
- **R = 100Ω**
- **C = 1μF**
- **f ≈ 1.59 kHz**

#### Gain Settings

- Positive feedback network attenuation: 1/3
- Negative feedback network gain: 3
- Total loop gain: 3 × (1/3) = 1 ✓

---

## 📁 Project Files

```
.
├── wienbridge.txt              # Main circuit file (can be imported in Falstad)
├── README.md                   # Project documentation (this file)
├── README_CN.md                # Chinese version of project documentation
```

---

## 🚀 Quick Start

### Online Simulation

1. Visit [Falstad Circuit Simulator](https://www.falstad.com/circuit/)
2. Click **File** → **Import from Text**
3. Copy and paste the content from `wienbridge.txt`
4. Click **Import**
5. Click **Run/Stop** to start simulation
6. Observe the sine wave output on the oscilloscope

### Expected Results

- 📈 **Waveform**: Stable sine wave
- 🎵 **Frequency**: Approximately 1.59 kHz
- ⚡ **Amplitude**: Approximately ±10V (limited by power supply voltage)
- 📉 **Distortion**: Low (< 1%)

---

## 🔧 Circuit Components

| Component | Value | Function |
|-----------|-------|----------|
| Operational Amplifier | Ideal Op-Amp | Active gain element |
| Resistors R1, R2 | 100Ω | RC network (positive feedback) |
| Resistor R3 | 1kΩ | Upper negative feedback resistor |
| Resistor R4 | 1kΩ | Lower negative feedback resistor |
| Capacitors C1, C2 | 1μF | RC network (positive feedback) |
| Diode D1 | Silicon Diode | Amplitude stabilization |

---

## 🎓 Learning Outcomes

Through this project, I have mastered the following knowledge and skills:

### Theoretical Knowledge
- ✅ Barkhausen Oscillation Criterion
- ✅ RC Frequency Selective Network
- ✅ Operational Amplifier Applications
- ✅ Feedback System Stability Analysis

### Practical Skills
- ✅ Circuit simulation tool usage (Falstad)
- ✅ Component selection and parameter calculation
- ✅ Parameter optimization and debugging
- ✅ Troubleshooting and problem solving

### Engineering Thinking
- ✅ Design process from theory to implementation
- ✅ System-level analysis and trade-offs
- ✅ Experimental verification and iterative optimization

---

## 🌟 Project Highlights

1. **Open Source Tools**: Uses completely free Falstad Circuit Simulator
2. **Text Format**: Circuit can be version controlled, easy to share and modify
3. **Real-time Simulation**: Visualizes current flow and waveform output
4. **Teaching Friendly**: Clear annotations and step-by-step instructions
5. **Extensibility**: Can serve as foundation for more complex circuits

---

## 🚀 Extended Applications

This project can serve as a foundation for the following applications:

- 🎛️ **Variable Frequency Oscillator**: Using variable resistors or capacitors
- 📐 **Function Generator**: Combined with integrators and comparators
- 🔒 **Voltage Controlled Oscillator (VCO)**: Using voltage-controlled resistors
- 🔧 **Practical Circuit Implementation**: Building actual circuits on breadboard

---

## 📚 References

1. [Falstad Circuit Simulator](https://www.falstad.com/circuit/)
2. Paul Horowitz, Winfield Hill. "The Art of Electronics" (3rd Edition)
3. Adel S. Sedra, Kenneth C. Smith. "Microelectronic Circuits"
4. [Wien Bridge Oscillator - Wikipedia](https://en.wikipedia.org/wiki/Wien_bridge_oscillator)

---
