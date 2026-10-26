# Requirements: Battery Thermal Management

Operating point: Operating point: one 12S1P module of Samsung SDI 94 Ah cells, cooling limit 400 W

| ID | Requirement | Checked under (test conditions) |
|---|---|---|
| REQ-01 | Battery temperature stays ≤ 40 °C | Normal load: 100 A, 25 °C ambient |
| REQ-02 | Battery temperature stays ≤ 45 °C | High load on a hot day: 150 A, 40 °C ambient |
| REQ-03 | Cooling turns ON above 35 °C and OFF below 30 °C | Load that heats up, then stops |
| REQ-04 | Above 55 °C → enter FAULT: full cooling and current limited to 50%; leave FAULT below 45 °C | Overheat case (for example, a cooling failure) |
| REQ-05 | Sensor reading outside −40 to 120 °C → enter SENSOR_FAULT: full cooling and current limited | Simulated broken sensor |
| REQ-06 | Cooling power always stays within 0–400 W | All scenarios |

