# PART 4: Traveling Wave & Wideband Antennas

---

# INTRODUCTION
While previous antennas were "resonant" (designed for one specific frequency), Traveling Wave and Wideband antennas are built to handle a massive range of frequencies without losing performance. These antennas allow waves to move along their structure rather than bouncing back and forth, which eliminates the "bottleneck" of a single-frequency design. This section covers specialized shapes that provide high gain and flexibility across the radio spectrum.

---

# ATENNAS

## Rhombic Antenna

<img width="471" height="185" alt="image" src="https://github.com/user-attachments/assets/640ba54f-65b0-4fb3-9793-39a0827acfca" />

The Rhombic antenna is a high-gain, traveling-wave antenna consisting of four long wires arranged in a diamond or "rhombus" shape. Unlike resonant antennas, it is typically terminated with a resistor at the far end, which forces the radio energy to move in one direction only. This design makes it one of the most effective antennas for long-distance, point-to-point communication.

| Distinct Physical Features | It consists of four long wires suspended above the ground in a diamond shape. Physically, each "leg" of the diamond is several wavelengths ($\lambda$) long, making it much larger than a standard dipole; the total perimeter is many times the size of a $\lambda/2$ antenna |
| :--- | :--- |

| Main Use | Long-range High Frequency (HF) point-to-point communication, such as international shortwave broadcasting |
| :--- | :--- |

## Log-Periodic Antenna (LPDA)

<img width="471" height="208" alt="image" src="https://github.com/user-attachments/assets/19030c76-3254-4b49-b410-dd3be31593b8" />

The Log-Periodic Dipole Array is a multi-element antenna designed to operate over an incredibly wide frequency range. It looks similar to a Yagi, but every single element is "active" and connected to the feed line. Because the lengths and spacings of the elements follow a logarithmic ratio, different parts of the antenna "take over" as the frequency changes.

| Distinct Physical Features | It consists of a sequence of dipoles that gradually increase in length from front to back. Physically, it looks like a "triangular" or "arrowhead" array where the shortest element is much smaller than $\lambda/2$ of the lowest frequency, and the longest element is $\lambda/2$ of the highest frequency |
| :--- | :--- |

| Main Use | All-band television reception (VHF/UHF), spectrum monitoring, and military communications where frequency-hopping is used |
| :--- | :--- |

## Zeppelin (Zepp) Antenna

<img width="471" height="221" alt="image" src="https://github.com/user-attachments/assets/fdc79f3f-bc3f-4e18-903c-8ee0cef8f2c6" />

The Zeppelin antenna, or "Zepp," is a horizontally polarized antenna that was originally designed for use on German airships. It is essentially a $\lambda/2$ wire that is fed at one end rather than in the center, using a specialized "matching stub" to handle the high impedance. This allows the antenna to be strung up easily between two points without a heavy cable hanging from the middle.

| Distinct Physical Features | It consists of a single long wire that is exactly $\lambda/2$ in length (half the wavelength). Physically, unlike a center-fed dipole which has a feedline in the middle, the Zepp is fed at the very tip, making the antenna look like a single, continuous straight wire suspended in the air |
| :--- | :--- |

| Main Use | Portable amateur radio setups and historical aeronautical communications where a simple, end-fed wire was easier to deploy than a center-fed one |
| :--- | :--- |
