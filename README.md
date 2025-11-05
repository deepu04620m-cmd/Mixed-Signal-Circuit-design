# Mixed Signal Circuit design
Design and Stability Analysis of a Two-Stage CMOS Operational Amplifier

## Overview of Two-Stage Operational Amplifier
A two-stage operational amplifier is designed to provide both high voltage gain and a large output swing, which are essential in many analog and mixed signal circuits. It consists of two main amplification stages.

The first stage is a differential amplifier that converts the input voltage difference into a current. This stage offers high input impedance and provides the initial gain while rejecting common-mode signals.

The second stage is a common-source amplifier that further amplifies the signal to achieve the desired overall gain and drives the load. Since cascading two stages can introduce phase shifts that may lead to instability, a compensation capacitor (commonly known as Miller capacitor) is used between the stages to control the frequency response and ensure stable operation.

Overall, the two-stage op-amp design achieves a balance between high gain, reasonable bandwidth, and stable operation, making it widely used in data converters, filters, and low-power analog systems.

## Design Steps
![dc](https://github.com/user-attachments/assets/c9e82f14-6352-4018-aafb-176b26e2b6fa)
![2](https://github.com/user-attachments/assets/58903dd0-dc23-4759-bb8e-803492562109)
![3](https://github.com/user-attachments/assets/cab2a937-662c-4cdd-ad05-7947f41dc518)

## Schematic
<img width="1920" height="1080" alt="Screenshot from 2025-11-05 12-49-35" src="https://github.com/user-attachments/assets/52e9bf0f-3387-48fb-ae9f-5aa596c4443a" />

## Symbol
<img width="1920" height="1080" alt="Screenshot from 2025-11-05 12-49-56" src="https://github.com/user-attachments/assets/dc6d5749-3454-4160-baef-20e012b4af66" />

## Test Circuit
<img width="1920" height="1080" alt="Screenshot from 2025-11-05 12-49-26" src="https://github.com/user-attachments/assets/86f160f0-034e-4879-8f73-e69cacdfdf62" />

# Results

## Transient Analysis
![trans](https://github.com/user-attachments/assets/07875690-3c83-46cd-ae96-ab37b203b5eb)

## AC Analysis
![ac](https://github.com/user-attachments/assets/aadb60ac-c157-4bb8-ac18-713ccf612ba3)

## Bode Plot
![bode](https://github.com/user-attachments/assets/7e22e688-ba81-420e-982b-8bf60dc23121)

## DC Analysis
![dc](https://github.com/user-attachments/assets/92b630a5-2832-42c0-9271-0eccb6570c25)


