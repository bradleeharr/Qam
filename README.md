# QAM Modulation




# Step 1: Data


1. Say we have a stream of data.

2. This data is represented in bits

3. These bits are what we want to transmit.

4. Using a digital encoding, symbols are assigned to bits of data. 


| Bit Chunk      | Symbol Number | 
| ----------- | ----------- |
| 00   | 1    |
| 01   | 2    |
| 10   | 3    |
| 11   | 4    |


Using digital modulation schemes, once we have assigned 'symbols' for each chunk of binary bits, we modulate them onto a carrier. This is where QAM comes in. In QAM, these symbols correspond to points with both real and imaginary parts, and an 'IQ' (In-phase and Quadrature) diagram is used to display the 'constellation' of a QAM format.


| Symbol Number | Amplitude | 
| ----------- | ----------- |
| 00   | 1 + 1j    |
| 01   | 1 - 1j    |
| 10   | -1 + 1j    |
| 11   | -1 - 1j    |

### Constellation Diagram

<p align="center">
<img src="https://github.com/bradleeharr/digital-qam-modulation/assets/56418392/8d4aa6f6-27a4-4a3d-9182-f7d8b17d2591" style="max-width:600px; width: 500px;"/>
</p>

### Upsampling and Modulation 

<p align="center">
<img src="https://github.com/bradleeharr/digital-qam-modulation/assets/56418392/fefbfcae-e875-48ae-a63b-3077b4fef8c5" style="max-width:800px; width:800px;"/>
</p>

### Pulse-Shaping 
