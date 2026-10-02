# Hardware Components

## Components

| Component | Quantity | Purpose |
|---|---:|---|
| ESP32 | 1 | Main microcontroller |
| FSR pressure sensors | 6 | Foot pressure sensing |
| MPU6050 | 1 | Motion and acceleration sensing |
| Resistors | 6 | FSR voltage-divider circuits |
| Orthotic insoles | 2 | Physical sensing platform |
| Connecting wires | As required | Electrical connections |
| Prototype board | 1 | Hardware assembly |

## Reference Pin Configuration

The following pin configuration corresponds to the ESP32 reference implementation in `Code/main.ino`.

| Component | ESP32 Pin |
|---|---|
| FSR 1 | GPIO 34 |
| FSR 2 | GPIO 35 |
| FSR 3 | GPIO 32 |
| FSR 4 | GPIO 33 |
| FSR 5 | GPIO 36 |
| FSR 6 | GPIO 39 |
| MPU6050 SDA | GPIO 21 |
| MPU6050 SCL | GPIO 22 |
