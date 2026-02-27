# PART 2: Yagi-Uda Arrays (High Directivity)

---

# INTRODUCTION
Yagi-Uda arrays represent a significant advancement in antenna design by utilizing parasitic elements to achieve high directivity and gain. Unlike fundamental dipoles that radiate energy in all directions, these arrays focus electromagnetic power into a concentrated beam, allowing for long-distance communication with reduced interference. By carefully arranging directors and reflectors around a central driven element, these systems transform a basic omnidirectional signal into a specialized directional tool.
Furthermore, these three pillars are fundamental to understanding the performance of directional arrays:
*	Resonance: In a Yagi-Uda system, only the driven element is directly connected to the source, yet the parasitic elements must be cut to specific lengths to achieve "parasitic resonance." This ensures that the induced currents are in the correct phase to reinforce the signal in the forward direction.
*	Impedance Matching: Adding multiple parasitic elements near the driven element lowers the antenna's natural input impedance. To maintain a standard or match, a Folded Dipole is often used as the driven element to step the impedance back up to a usable level.
*	Radiation Resistance: The concentration of power into a narrow beam effectively increases the "apparent" radiation resistance in the forward direction, known as gain. This allows the antenna to transmit more effectively toward a specific target while virtually eliminating radiation in the opposite direction.

---

# TYPES OF ANTENNAS

## Yagi-Uda Simple 5-Element

<img width="471" height="316" alt="image" src="https://github.com/user-attachments/assets/6abe429d-b050-4b51-9134-bbc71387d372" />

The 5-element Yagi is a classic "mid-range" directional antenna that balances size with performance. It consists of one reflector, one driven element (simple dipole), and three directors. By adding more directors than a basic 3-element version, it achieves a tighter radiation pattern and higher forward gain.

| Distinct Physical Features | It utilizes a simple straight dipole as the driven element, which consists of two separate rods. Physically, the total length of the driven dipole is λ/2 (half-wavelength), while the directors are progressively shorter and the reflector is slightly longer |
| :--- | :--- |

| Main Use | Point-to-point communication in VHF/UHF bands where a moderate increase in signal strength is needed without a massive boom length |
| :--- | :--- |

## Yagi-Uda Simple 7-Element

<img width="471" height="265" alt="image" src="https://github.com/user-attachments/assets/851f7100-4cb1-4dbf-a3ea-f4e326e6f03d" />

This version pushes the directivity further by adding two more directors to the array. The increased number of elements narrows the "beamwidth" significantly, meaning you have to point it very precisely at the target. It offers a much higher front-to-back ratio, effectively ignoring interference coming from behind the antenna.

| Distinct Physical Features | This is a long-boom antenna where the total length of the supporting structure is significantly greater than the 5-element version. Like the 5-element, it uses a straight λ/2 dipole, but the added directors make the physical profile much thinner and longer |
| :--- | :--- |

| Main Use | Long-distance (DX) communication and fringe-area television reception where the signal is very weak and requires maximum "reach." |
| :--- | :--- |

## Yagi-Uda Folded Dipole 3-Element

<img width="471" height="279" alt="image" src="https://github.com/user-attachments/assets/4814b7e5-a99f-4a63-bee9-c9b433df731c" />

This is a compact, high-performance array that swaps the standard straight dipole for a folded one. The 3-element design (one reflector, one folded driven element, and one director) is the foundational "high-gain" antenna design. It is prized for its durability and better impedance matching.

| Distinct Physical Features | The driven element is a folded dipole, which looks like a continuous loop or a "paperclip" shape. While its total length remains λ/2, the "folded" design means the antenna has two parallel conductors joined at the ends, making it physically more robust than two separate rods |
| :--- | :--- |

| Main Use | FM radio reception and residential rooftop TV antennas, as the folded dipole handles wide bandwidths and weather better than a simple dipole |
| :--- | :--- |

## Yagi-Uda Folded Dipole 5-Element

<img width="571" height="300" alt="image" src="https://github.com/user-attachments/assets/6d953b33-b724-4ce2-942c-1cfe8d36d387" />

This configuration combines the high gain of a 5-element array with the electrical benefits of a folded dipole. It provides a very "clean" signal with high input impedance, which is often easier to match to standard 300-ohm or 75-ohm (with a balun) cabling. It strikes an excellent balance between high directivity and broad frequency response.

| Distinct Physical Features | It features the same λ/2 folded loop as the 3-element version but is surrounded by four additional straight parasitic elements (1 reflector and 3 directors). This gives it a "ladder-like" appearance with a prominent looped element in the second position from the back |
| :--- | :--- |

| Main Use | Professional telecommunications and ham radio where a stable, high-gain connection is required across a slightly wider range of frequencies |
| :--- | :--- |
