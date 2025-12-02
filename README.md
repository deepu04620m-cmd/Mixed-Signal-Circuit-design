# Mixed Signal Circuit design
Design and Stability Analysis of a Two-Stage CMOS Operational Amplifier

## Overview of Two-Stage Operational Amplifier
A two-stage operational amplifier is designed to provide both high voltage gain and a large output swing, which are essential in many analog and mixed signal circuits. It consists of two main amplification stages.

The first stage is a differential amplifier that converts the input voltage difference into a current. This stage offers high input impedance and provides the initial gain while rejecting common-mode signals.

The second stage is a common-source amplifier that further amplifies the signal to achieve the desired overall gain and drives the load. Since cascading two stages can introduce phase shifts that may lead to instability, a compensation capacitor (commonly known as Miller capacitor) is used between the stages to control the frequency response and ensure stable operation.

Overall, the two-stage op-amp design achieves a balance between high gain, reasonable bandwidth, and stable operation, making it widely used in data converters, filters, and low-power analog systems.

## Design Steps
![WhatsApp Image 2025-11-05 at 13 13 42_f2eb1fa1](https://github.com/user-attachments/assets/e938293e-87fb-4954-9605-efe7c79f1867)
![2](https://github.com/user-attachments/assets/58903dd0-dc23-4759-bb8e-803492562109)
![3](https://github.com/user-attachments/assets/cab2a937-662c-4cdd-ad05-7947f41dc518)

## Schematic
<img width="1920" height="1080" alt="Screenshot from 2025-12-02 14-13-43" src="https://github.com/user-attachments/assets/148ffb0a-f0ea-40dd-ae65-2dedb527f155" />


## Symbol
<img width="1920" height="1080" alt="Screenshot from 2025-11-05 12-49-56" src="https://github.com/user-attachments/assets/dc6d5749-3454-4160-baef-20e012b4af66" />

## Test Circuit
<img width="1920" height="1080" alt="Screenshot from 2025-11-05 12-49-26" src="https://github.com/user-attachments/assets/86f160f0-034e-4879-8f73-e69cacdfdf62" />

# Results

## Transient Analysis
<img width="1920" height="1080" alt="Screenshot from 2025-12-02 15-38-04" src="https://github.com/user-attachments/assets/a59254aa-3777-4f4d-9c47-fa80bddb8247" />


## AC Analysis
<img width="1920" height="1080" alt="Screenshot from 2025-12-02 14-12-13" src="https://github.com/user-attachments/assets/aff55d2c-017c-4924-aadb-f1cc388923d0" />


## Bode Plot
<img width="1920" height="1080" alt="Screenshot from 2025-12-02 13-36-05" src="https://github.com/user-attachments/assets/ab36e0e8-b6dd-4795-8073-b37bba496821" />


## DC Analysis
<img width="1920" height="1080" alt="Screenshot from 2025-12-02 14-12-39" src="https://github.com/user-attachments/assets/64372b66-e565-4165-ba28-73165bf44795" />



