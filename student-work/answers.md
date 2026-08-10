# Assignment 00 — Student Answer Sheet

## Student Information

| Field | Student Response |
|---|---|
| Full name | `nisha anilsingh gaherwar` |
| GitHub username | `hii-nish` |
| Class/college | `shankarlal khandelwal college bca 3rd year` |
| Submission date | `10 Aug` |

---

## Section A — Industrial Automation Fundamentals (15 marks)

### Q1. What is industrial automation? Explain it in 3–5 sentences. (5 marks)

`Core idea  of industrial automation  is using machines, sensors, and controllers instead of people to run a process automatically.it replaces manual operation with automatic control like PLC, sensors, actuators, the goal is minimal human intervention, and it makes production faster, more consistent, and safer.`

### Q2. State any four reasons industries use automation. (4 marks)

1. `lower labour cost`
2. `higher productivity`
3. `improved safety`
4. `more consistently `

### Q3. Give three examples of processes that can be automated using PLC and SCADA. (3 marks)

1. `water treatment `
2. `oven temperature control`
3. `botteling and packeging of products`

### Q4. Complete the automation sequence. (3 marks)

```
Input → Processing → Control → Output
```

Explain the meaning of each stage:

`Input: sensors collects data or information from machine or environment 
Processing : plc perform operations on data collected data 
Control: plc send control signals to machine
Output: device perform required action according to the given signals 
 `


---

## Section B — PLC Fundamentals and Working (25 marks)

### Q5. Expand PLC and explain why it is called an industrial computer. (5 marks)

`PLC stands for Programmable Logic Controller. It's called an industrial computer because it has the same core parts as a computer like processor, memory, I/O — but it's built to survive factory conditions like heat, dust, vibration, electrical noise and it's dedicated to running one control program repeatedly, not general apps.`

### Q6. Classify each device as a PLC input or PLC output. (5 marks)

| Device | Input or Output? |
|---|---|
| Push button | `input` |
| Proximity sensor | `input` |
| Motor contactor | `output` |
| Indicator lamp | `output` |
| Temperature sensor | `input` |

### Q7. Write the three main PLC working steps in the correct order. (6 marks)

1. `Input Scan`
2. `Program Scan`
3. `Output Scan`

### Q8. What is a PLC scan cycle? Why must it repeat continuously? (5 marks)

`It's one full round of the three steps i.e., input scan , program scan, output scan. It has to repeat nonstop because real-world conditions change constantly — a sensor can trip at any moment — and a PLC that only ran once could never react to anything after that. Continuous scanning is what makes it responsive in near real-time.`

### Q9. Identify the PLC section responsible for each function. (4 marks)

| Function | PLC Section |
|---|---|
| Executes the user program | `cpu` |
| Stores the program and data | `memory` |
| Reads field-device signals | `input module ` |
| Controls external devices | `output module` |

---

## Section C — SCADA Fundamentals (20 marks)

### Q10. Expand SCADA and explain its purpose. (5 marks)

`SCADA stands for Supervisory Control and Data Acquisition. Its purpose is letting operators monitor and control processes spread across a wide area from one central place, by collecting real-time data and giving them a way to see and respond to it.`

### Q11. State five important functions of a SCADA system. (5 marks)

1. `Data Acquisition `
2. `Real Time Data Collection`
3. `Data Storing`
4. `Alarm`
5. `Monitoring `

### Q12. Why is SCADA described as the “eyes” of an automation system? (4 marks)

`Because it gives operators visibility into what's happening everywhere at once, on a screen, without them physically standing next to every machine.`

### Q13. Name four industries or services where SCADA can be used. (4 marks)

1. `Water Treatment `
2. `Oil/Gas pipelines`
3. `Manufacturing`
4. `Traffic Control System`

### Q14. What is the difference between monitoring and controlling? (2 marks)

`Monitoring means watching or reading current status, no changes made While Controlling means actively changing something (on/off, setpoints) based on what's observed.`

---

## Section D — PLC, HMI and SCADA Relationship (15 marks)

### Q15. Complete the comparison table. (9 marks)

| System | Main purpose | Typical user/location | Example task |
|---|---|---|---|
| PLC | `real time control ` | `Control Panel ` | `Switches a motor on when a sensor triggers` |
| HMI | `Local interface ` | `machine opertor` | `Displaying real-time temperature graph` |
| SCADA | `high level control` | `central control room` | `Engineer watches tank levels at five stations from one office` |

### Q16. Explain how information travels from a field sensor to a SCADA screen. (6 marks)

`I have no idea about this topic`

---

## Section E — Industrial Application Challenge (15 marks)

### Scenario: Automatic Water Tank

A tank must fill automatically. A low-level sensor detects when water is low, and a high-level sensor detects when the tank is full. A pump supplies water. The operator should see the tank and pump status on a monitoring screen.

### Q17. Identify the PLC inputs and output. (3 marks)

- Inputs: `high and low level sensors`
- Output: `water pump`

### Q18. Write the required control behaviour in plain language. (4 marks)

`When low level sensors says water level is low PLC switches the pump ON, When high level says water level is full then PLC switches the pump OFF`

### Q19. State four items that should be visible on the SCADA/HMI screen. (4 marks)

1. `Current water level`
2. `Pump on off switches`
3. `status of both sensors `
4. `any activity alarm `

### Q20. Suggest one alarm and one value/event that should be recorded. (4 marks)

- Alarm: `Tank is overflowing warning`
- Recorded value/event: `time stamp of ON-OFF status`

---

## Submission Checklist

- [x] I entered my student information.
- [x] I answered Questions 1–20.
- [x] I used my own words.
- [x] I checked spellings and technical terms.
- [x] I completed `student-work/reflection.md`.
- [x] I made at least three meaningful commits.
- [x] I checked the Actions result.
- [x] I submitted my repository link to Prof. Dattaraj Vidyasagar.
