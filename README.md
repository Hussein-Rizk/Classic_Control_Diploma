# Classic Control & PLC Diploma

Practical industrial control and automation training covering **classic electrical control, PLC programming, ladder logic, circuit simulation, and industrial process simulation**.

This repository documents exercises completed throughout the diploma using:

- **CADe_SIMU** for classic electrical control circuits
- **LogixPro PLC Simulator** for PLC ladder-logic programming and process simulation
- **Siemens TIA Portal** — to be added

---

## ⚡ 1. Classic Control — CADe_SIMU

The first part of the diploma focused on designing and understanding traditional electrical control circuits before moving to PLC-based automation.

The general workflow was:

1. Analyze the required control sequence
2. Design the power and control circuits
3. Build the circuit using **CADe_SIMU**
4. Simulate and verify the circuit behavior
5. Troubleshoot wiring and logic
6. Apply the same concepts to practical electrical-control hardware

### CADe_SIMU Example

<p align="center">
  <img src="Classic%20Control%20Tasks/CADe_Simu.gif"
       alt="CADe SIMU Classic Control Simulation"
       width="850">
</p>

### Concepts Practiced

- Power and control circuits
- Start / Stop circuits
- Contactors and auxiliary contacts
- Electrical interlocking
- Motor-control circuits
- Timer-based control
- Sequential operation
- Relay / contactor logic
- Multiple-motor control
- Circuit troubleshooting

The original CADe files are preserved together with recorded simulations showing the operation of the circuits.

---

# 🧠 2. PLC Programming — LogixPro

The next stage of the diploma introduced **Programmable Logic Controllers (PLCs)** using the **LogixPro PLC Simulator**.

The exercises were programmed using **ladder logic** and tested against LogixPro's built-in industrial process simulators.

Original `.rsl` PLC programs are included together with recorded simulation videos.

## LogixPro Simulation Example

<p align="center">
  <img src="PLC%20Logix%20Pro%20Tasks/PLC_LogixPro.gif"
       alt="LogixPro PLC Ladder Logic Simulation"
       width="850">
</p>

The example above shows ladder logic running online while interacting with the **Batch Mix process simulator**, allowing PLC inputs, outputs, counters, and process states to be observed during execution.

---

## 🪜 Ladder Logic Concepts

The LogixPro exercises included practical work with concepts such as:

- PLC inputs and outputs
- Ladder logic programming
- Start / Stop logic
- Latching logic
- Timers
- Counters
- Comparison instructions
- One-shot instructions
- Status / state retention
- Sequential control
- Motor sequencing
- Forward / reverse control
- Repetitive machine cycles
- Process automation
- PLC troubleshooting and online monitoring

---

## 🏭 LogixPro Process Simulations

Several built-in LogixPro process environments were used to test the PLC programs.

### 🧪 Batch Mix Simulator

Exercises involving automated batch-processing sequences using components such as:

- Pumps
- Flowmeters
- Mixer
- Heater
- Level sensors
- Thermostat
- PLC-controlled filling and processing stages

PLC ladder logic was monitored online while the simulated process responded to the program.

---

### 🚪 Door Simulator

PLC exercises were also developed and tested using the **door simulation environment**, providing practice with sequence and state-based control.

---

### ⚙️ Motor-Control Exercises

Multiple exercises focused on controlling motors using ladder logic, including:

- Multiple-motor sequences
- Repeated motor operation
- Sequential activation
- Forward / reverse control
- Start / Stop behavior

---

### ⏱️ Timer & Counter Exercises

Exercises included control sequences based on:

- Timed ON/OFF operation
- Counters
- Repeated cycles
- Comparison conditions
- One-shot logic

Examples in the original files include timing exercises such as **5-second ON / 2-second OFF** operation and counter-based control.

---

### 📊 Process & Input/Output Exercises

Additional exercises explored PLC input/output behavior and process conditions, including pressure-related simulation cases and different control solutions.

---

## 🔄 Training Progression

```text
Classic Electrical Control
          │
          ▼
    CADe_SIMU Design
          │
          ▼
 Virtual Circuit Testing
          │
          ▼
 Relay / Contactor Logic
          │
          ▼
     PLC Fundamentals
          │
          ▼
  LogixPro Ladder Logic
          │
          ▼
Industrial Process Simulation
          │
          ▼
   Siemens TIA Portal
       (Coming Next)
