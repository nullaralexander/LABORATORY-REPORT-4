# EXPERIMENT  4: Transmission and Reception of Signals Using Two Antennas (TX and RX)

---

# I. INTRODUCTION
Antenna systems play a vital role in wireless communication by enabling the transmission and reception of electromagnetic signals through free space. In any communication system, a transmitting antenna converts electrical signals into electromagnetic waves, while a receiving antenna captures these waves and converts them back into electrical signals for analysis and processing.

This experiment focuses on establishing a successful wireless link between two antennas—a transmitting antenna (TX) and a receiving antenna (RX)—using an audio generator as the signal source. The transmitted signal is radiated through the antenna trainer and detected by the receiving antenna. An RF detector and an oscilloscope are used to verify the presence, stability, and frequency of the received signal.

By properly setting up the equipment and aligning the antennas, the experiment aims to demonstrate effective signal transmission and reception, with the received waveform observed on the oscilloscope at an approximate frequency of 2 kHz. This experiment reinforces fundamental concepts of antenna operation, signal propagation, and wireless communication measurement techniques.

---

# II. OBJECTIVES
At the end of this experiment, the students should be able to:

* To understand the basic principles of antenna transmission and reception.

* To properly set up a two-antenna system consisting of a transmitter (TX) and a receiver (RX).

* To generate a low-frequency signal using an audio generator and transmit it through an antenna.

* To successfully receive the transmitted signal using a receiving antenna and RF detector.

* To observe and measure the received signal waveform and frequency using an oscilloscope.

* To verify that the received signal frequency is approximately 2 MHz, confirming successful wireless transmission.

---

# III. MATERIALS

| Item | Description |
| :--- | :--- |
| **Antenna Trainer** | Serves as the main platform and power source for antenna transmission and reception experiments |
| **Transmitting Antenna (TX)** | Radiates the signal from the transmitter into free space |
| **Receiving Antenna (RX)** | Captures the transmitted signal from the transmitting antenna |
| **Audio Generator** | Generates the input signal (approximately 2 MHz) for transmission |
| **RF Detector** | Detects and converts the received RF signal into a measurable output |
| **Oscilloscope** | Displays and measures the received signal waveform and frequency |
| **Connecting Cables and Patch Cords** | Used to interconnect the equipment properly |

---

# IV. EXPERIMENTAL RESULTS

## Experiment Circuit Procedure
### A. Transmitter Side

1. Set up the antenna trainer as the main unit for signal transmission.

2. Connect the audio generator to the input terminal of the antenna trainer.

3. Set the audio generator to generate a sinusoidal signal with a frequency of approximately 2 MHz.

4. Connect the transmitting antenna (TX) to the output terminal of the antenna trainer.

![IMG_20260213_093224](https://github.com/user-attachments/assets/6ea6358f-2cf2-4679-8c08-84d1121de69f)

![IMG_20260213_093147](https://github.com/user-attachments/assets/0035fbf8-ac7e-4166-9d69-4d5be9556541)

https://github.com/user-attachments/assets/5356dc3f-a9b5-4c0c-8001-c7fb27a95494

### B. Receiver Side
1. Position the receiving antenna (RX) at a suitable distance from the transmitting antenna.

2. Connect the receiving antenna to the RF detector.

3. Connect the output of the RF detector to the oscilloscope probes.

4. Power on the oscilloscope and adjust the time base and voltage scale for proper signal display.

5. Confirm that the received waveform shown on the oscilloscope has a frequency of approximately 2 MHz, indicating successful signal transmission and reception.

![IMG_20260213_093307](https://github.com/user-attachments/assets/eaf1a46d-f78e-4860-bbc3-b756ff4ef7c0)

![IMG_20260213_093202](https://github.com/user-attachments/assets/b91be912-d5d3-4b2d-b0f0-21f42b853ed2)

https://github.com/user-attachments/assets/9cc209eb-2423-4ea9-821c-426b6b12295a

---

# V. OBSERVATION
The performance of our wireless transmission system greatly depends on the type of antenna used, particularly its directivity, bandwidth, and alignment requirements. In this experiment, we evaluated different antenna types to determine their effectiveness in transmitting and receiving a signal at 2 MHz.

Initially, we used a small directivity antenna as the transmitting antenna. This antenna has limited gain and low radiation efficiency at lower frequencies such as 2 MHz, where the wavelength is relatively long. Because the physical size of the antenna is small compared to the wavelength, it was unable to efficiently radiate electromagnetic energy. As a result, we were not able to observe the required output frequency at the receiving antenna.

Next, we replaced the transmitting antenna with a Yagi-Uda Simple 7-Element antenna. This antenna provides high gain and strong directivity, which theoretically improves signal strength. However, its narrow beamwidth required very precise alignment between the transmitting and receiving antennas. During our setup, slight misalignment caused significant signal loss, preventing us from receiving the required output signal at the RX antenna.

To solve this problem, we decided to use a Log-Periodic Antenna (LPDA) as the transmitting antenna. The LPDA is designed for wide-band operation and offers more stable performance over a range of frequencies. Its moderate directivity and wider bandwidth made alignment easier and improved signal coverage at 2 MHz. With this configuration, we successfully received the required 2 MHz output signal at the receiving antenna.

From this experiment, we concluded that proper antenna selection is critical for successful signal transmission and reception. Antennas with wide bandwidth and manageable directivity, such as the LPDA, are more suitable for low-frequency experimental setups and provide more reliable results.

![IMG_20260213_093020](https://github.com/user-attachments/assets/69a28314-7086-4590-94e4-1f7eab63d9dd)

https://github.com/user-attachments/assets/71f95e1a-9c12-4df0-b223-400f8a792015

https://github.com/user-attachments/assets/ca7d5460-ee0c-48e1-9c83-ca21f923ba4d

---


# VI. CONCLUSION 
In this experiment, we successfully demonstrated the transmission and reception of signals using two antennas (TX and RX). By properly setting up the antenna trainer, audio generator, RF detector, and oscilloscope, we were able to establish a wireless communication link and observe the received signal at an approximate frequency of 2 MHz. This confirmed that electromagnetic signals can be effectively transmitted through free space and accurately detected using appropriate receiving equipment.

I observed that antenna performance strongly depends on design characteristics such as directivity, bandwidth, and alignment. The initial use of a small directivity antenna and a Yagi-Uda Simple 7-Element antenna did not produce the required output due to low radiation efficiency and strict alignment requirements, respectively. From this, I learned the importance of selecting an antenna suitable for the operating frequency and experimental setup.

By using a Log-Periodic Antenna (LPDA), we were able to overcome these limitations. Its wide bandwidth and moderate directivity allowed easier alignment and more stable signal transmission, resulting in the successful reception of the required 2 MHz signal at the receiving antenna. Overall, I learned how antenna characteristics affect signal transmission and reception, and I gained a deeper understanding of proper antenna selection for reliable wireless communication.

