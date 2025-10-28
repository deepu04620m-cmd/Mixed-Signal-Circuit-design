# Mixed-Signal-Circuit-design
Design and Stability Analysis of a Two-Stage CMOS Operational Amplifier

## Overview of Two-Stage Operational Amplifier
A two-stage operational amplifier is designed to provide both high voltage gain and a large output swing, which are essential in many analog and mixed signal circuits. It consists of two main amplification stages.

The first stage is a differential amplifier that converts the input voltage difference into a current. This stage offers high input impedance and provides the initial gain while rejecting common-mode signals.

The second stage is a common-source amplifier that further amplifies the signal to achieve the desired overall gain and drives the load. Since cascading two stages can introduce phase shifts that may lead to instability, a compensation capacitor (commonly known as Miller capacitor) is used between the stages to control the frequency response and ensure stable operation.

Overall, the two-stage op-amp design achieves a balance between high gain, reasonable bandwidth, and stable operation, making it widely used in data converters, filters, and low-power analog systems.

## Schematic
<img width="1920" height="1080" alt="Screenshot from 2025-10-28 13-27-15" src="https://github.com/user-attachments/assets/777893dc-4a2e-443a-aaf2-acfc1add7a07" />

## Symbol
<img width="1920" height="1080" alt="Screenshot from 2025-10-28 13-27-24" src="https://github.com/user-attachments/assets/0b8d5bab-ceae-46d7-b261-770d2765d9f6" />
