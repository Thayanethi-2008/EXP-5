# EXPERIMENT NO. 5 – ZENER DIODE AS VOLTAGE REGULATOR

| **Name:THAYANETHI| | **Reg. No.:26018113| |
|---|---|---|---|
| **Date:25-11-26 | | **Batch / Section:19EE305 | |

---

## AIM

To study the Zener diode as a voltage regulator and to obtain its line regulation and load regulation characteristics.

## APPARATUS REQUIRED

| S. No. | Name of the apparatus | Range | Quantity |
|:---:|:---:|:---:|:---:|
| 1 | Zener diode | 1N4735A | 1 |
| 2 | Resistors | 1 kΩ, 10 kΩ | 1 each |
| 3 | Regulated power supply | (0–30) V DC | 1 |
| 4 | Breadboard | — | 1 |
| 5 | Digital ammeter | (0–200) mA | 1 |
| 6 | Digital voltmeter | (0–20) V DC | 1 |
| 7 | Decade resistance box (load RL) | — | 1 |
| 8 | Connecting wires | — | As required |
| 9 | Simulation software | Proteus Design Suite | 1 |

## THEORY

A Zener diode is a heavily doped p-n junction diode, specially made to operate in the breakdown region. When reverse biased beyond a particular voltage, called the Zener breakdown voltage (Vz), it starts conducting heavily. Once it conducts, it maintains an almost constant voltage across its terminals whatever the current through it, i.e. it has a very low dynamic resistance. A series resistor Rs is connected to limit the current, since a high current can permanently damage the device.

In a Zener voltage regulator, the Zener diode is connected in reverse bias in parallel with the load, and the series resistor Rs is connected between the supply and the load. Any change in input voltage or load current changes the Zener current, while the output voltage across the load stays nearly constant at Vz.

**Line regulation:** the ability of the regulator to keep the output voltage constant when the input voltage varies, with the load kept constant.

**Load regulation:** the ability of the regulator to keep the output voltage constant when the load resistance (load current) varies, with the input voltage kept constant.

## PRECAUTIONS

1. While doing the experiment, do not exceed the ratings of the Zener diode; this may damage the diode.
2. Connect the voltmeter and ammeter in correct polarities as shown in the circuit diagram.
3. Do not switch ON the power supply unless the circuit connections have been checked as per the circuit diagram.

## PROCEDURE

### A. Line regulation

1. Connections are made as per the line regulation circuit diagram, with a fixed load resistance RL.
2. Vary the regulated power supply (input) voltage Vin in steps.
3. For each input voltage, note the output voltage Vo across the load and tabulate the readings.
4. Plot a graph of input voltage Vin (x-axis) versus output voltage Vo (y-axis).

### B. Load regulation

1. Connections are made as per the load regulation circuit diagram.
2. Set the input voltage Vin to a constant value above the Zener voltage.
3. Note the no-load output voltage VNL with the load disconnected.
4. Connect the load and vary the load resistance RL in steps; note the output voltage Vo for each value and tabulate the readings.
5. Plot a graph of load resistance RL (x-axis) versus output voltage Vo (y-axis).

## CIRCUIT DIAGRAM

### A. Line regulation

<img width="1600" height="798" alt="WhatsApp Image 2026-11-24 at 8 49 35 PM" src="https://github.com/user-attachments/assets/15053789-505c-49ae-9ee5-235226855b86" />


### B. Load regulation

<img width="1412" height="812" alt="WhatsApp Image 2026-11-24 at 8 49 45 PM" src="https://github.com/user-attachments/assets/ae672406-212f-4617-a6f5-deb3ef754784" />


## SIMULATION USING PROTEUS

Build the Zener regulator circuit in Proteus using the 1N4735A, the series resistor and the load. Vary the input voltage (line regulation) and the load resistance (load regulation), and paste screenshots showing the meter readings.

<img width="1519" height="685" alt="Screenshot 2026-11-15 132427" src="https://github.com/user-attachments/assets/f995ad9d-f2ab-4c50-a4f1-49bacc93326a" />
<img width="1497" height="703" alt="Screenshot 2026-11-15 132509" src="https://github.com/user-attachments/assets/0dba15c1-46fb-4c45-bc83-2556b2a82cd3" />


## TABULATION

### A. Line regulation 
<img width="1400" height="812" alt="WhatsApp Image 2026-11-24 at 8 57 36 PM" src="https://github.com/user-attachments/assets/2603a149-1b83-4a4a-a321-d94898ec3e5a" />




### B. Load regulation
<img width="1400" height="812" alt="WhatsApp Image 2026-11-24 at 8 57 42 PM" src="https://github.com/user-attachments/assets/80e8c7d8-a7c1-4482-b7fd-b1b384c9cbab" />





## FORMULAE

- **% Line regulation = (ΔVo / ΔVin) × 100**
- **% Load regulation = (VNL − VFL) / VFL × 100**
- **Series resistance Rs = (Vin − Vz) / (Iz + IL)**

ΔVo – change in output voltage; ΔVin – change in input voltage; VNL – no-load output voltage; VFL – full-load output voltage; Vz – Zener voltage; Iz – Zener current; IL – load current.

## MODEL GRAPH

### A. Line regulation (Vin vs Vo)


<img width="1400" height="803" alt="WhatsApp Image 2026-11-24 at 8 57 50 PM" src="https://github.com/user-attachments/assets/c038407d-2992-4ff4-a548-eb0ed2985c93" />


### B. Load regulation (RL vs Vo)
<img width="1400" height="868" alt="WhatsApp Image 2026-11-24 at 8 57 56 PM" src="https://github.com/user-attachments/assets/ba784ccd-79a8-415a-bd13-461e7ecddce2" />


## RESULT

Thus, the Zener diode was used as a voltage regulator, and its line regulation and load regulation characteristics were obtained.
