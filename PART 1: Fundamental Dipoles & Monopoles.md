# PART 1: Fundamental Dipoles & Monopoles

---

# INTRODUCTION
The study of antenna theory begins with the analysis of Fundamental Dipoles and Monopoles, which serve as the essential building blocks for nearly all modern wireless communication systems. These antennas are characterized by their ability to convert electrical energy into electromagnetic waves through resonant current distribution along a conductive element. In this section, the research focuses on the relationship between physical geometry and electrical performance, specifically examining how variations in wavelength—such as the λ 2 and 3/2λ configurations—alter radiation characteristics. By observing the behavior of the Hertz antenna and the Ground Plane monopole, we can evaluate the foundational principles of omnidirectional radiation and the effects of "Image Theory" on vertical radiators.
Furthermore, these three pillars are fundamental to understanding antenna performance:
*	Resonance: This occurs when an antenna's physical length is electrically matched to the operating frequency, causing inductive and capacitive reactances to cancel out. At resonance, the antenna efficiently accepts power from the source, minimizing the Standing Wave Ratio (SWR) and reflected energy.
*	Impedance Matching: This is the process of aligning the antenna’s input impedance with the characteristic impedance of the transmission line (typically 50 or 75Ω). Proper matching ensures maximum power transfer; for example, a standard Simple λ/2 Dipole presents roughly 73Ω, whereas a Folded Dipole transforms this to approximately 300Ω.
*	Radiation Resistance: This is a conceptual resistance representing the power successfully converted into electromagnetic waves. A higher radiation resistance relative to ohmic (heat) resistance indicates a more efficient radiator, as seen in the λ4 Ground Plane antenna, which uses a conductive surface to maintain effective radiation despite its reduced physical size.

---

# TYPES OF ANTENNAS

## Hertz Antenna

<img width="471" height="265" alt="image" src="https://github.com/user-attachments/assets/d9e89996-38cc-4cc9-8dcb-f2285324e61e" />


The Hertz antenna is the most elementary radiator used to demonstrate the basic principles of electromagnetic wave propagation. In this specific configuration, the antenna is characterized by having only a single radiating arm connected to the signal source. This setup is utilized in laboratory environments to observe how a lone conductor generates an electric field without the symmetry of a traditional dipole.

| Distinct Physical Features | Unlike standard dipoles, it features only one straight arm. Physically, it is half the size of a λ/2 dipole, representing a single-pole radiator |
| :--- | :--- |

| Main Use | Used for basic field induction experiments and to demonstrate the simplest possible form of an open-circuit radiator |
| :--- | :--- |

## Simple Dipole λ/4

<img width="471" height="239" alt="image" src="https://github.com/user-attachments/assets/19b45954-19b0-4fe2-b63f-f19d83a82e90" />

The λ/4 dipole is a compact resonant structure designed for applications where space is a limiting factor. It consists of two straight arms aligned collinearly, with each arm measuring one-eighth of a wavelength (λ/8) to reach its total length. While smaller than the standard reference antenna, it still maintains a balanced feed system.

| Distinct Physical Features | It consists of two straight arms fed at the center. It is physically half the size of a standard λ/2 dipole, making it significantly more compact |
| :--- | :--- |

| Main Use | Primarily used in portable or handheld communication devices where a small physical footprint is required for the antenna |
| :--- | :--- |

## Simple Dipole λ /2

<img width="471" height="231" alt="image" src="https://github.com/user-attachments/assets/6cac75a0-b0ea-4502-8de8-bdccf5979009" />

The half-wave (λ/2) dipole is the global standard reference for antenna gain and radiation pattern analysis. It is composed of two straight collinear arms, each measuring λ/4, which allows the antenna to reach a natural state of electrical resonance. At this specific length, the antenna exhibits a balanced "doughnut-shaped" radiation pattern that provides a reliable baseline for RF measurements.

| Distinct Physical Features | It features two straight arms that span a total distance of half a wavelength. Physically, it is twice the size of the λ/4 dipole and represents the most common resonant radiator |
| :--- | :--- |

| Main Use | The primary reference for measuring antenna gain and the most common element used for FM radio and TV reception |
| :--- | :--- |

## Simple Dipole 3/2 λ 

<img width="471" height="243" alt="image" src="https://github.com/user-attachments/assets/106245c3-de4e-4c61-af9e-bebf055f5331" />

The 3/2λ dipole is a high-order harmonic antenna that operates at three times the fundamental resonant frequency of a standard λ/4 arm. Due to its extended length, the current distribution along the conductors undergoes multiple phase reversals. This physical expansion results in a complex radiation pattern characterized by multiple lobes and nulls rather than a single broad beam.

| Distinct Physical Features | It consists of two straight arms that are much longer than the standard version. Physically, it is three times the size of the λ/2 dipole, which drastically changes its electromagnetic profile |
| :--- | :--- |

| Main Use | : Used for specialized long-range HF communications and to study the behavior of harmonic standing waves on long-wire radiators |
| :--- | :--- |

## Folded Dipole λ/2

<img width="471" height="226" alt="image" src="https://github.com/user-attachments/assets/e288c242-0777-407f-9152-a1ee8dc466e7" />

The folded dipole is a variation of the standard half-wave antenna that incorporates a parallel return path for the current. By connecting two λ/2 elements at the ends, it forms a continuous, narrow loop that significantly alters the antenna's electrical properties. This design provides a much wider bandwidth and a higher input impedance compared to a single-wire dipole.

| Distinct Physical Features | Unlike the simple dipole's two separate rods, the folded dipole uses a continuous, folded conductor forming a narrow loop. While it has the same end-to-end span as a simple λ/2 dipole, it uses twice the amount of conductive material |
| :--- | :--- |

| Main Use | Widely used in FM radio and television broadcasting because its folded shape provides a 300 Ω impedance match and improved bandwidth |
| :--- | :--- |

## Ground Plane

<img width="471" height="292" alt="image" src="https://github.com/user-attachments/assets/d37450ad-ba84-440f-8035-86cce38d80aa" />

The ground plane antenna is a vertical radiator designed to operate effectively without a second symmetrical arm. It utilizes a single vertical λ/4 "whip" paired with a set of horizontal or sloped radials at the base that act as a surrogate ground. These radials create an electromagnetic "image" of the vertical element, effectively completing the circuit to mimic a full dipole.

| Distinct Physical Features | It features a single vertical λ/4 arm supported by several horizontal or sloped rods at the base. These radials physically substitute for the "missing" arm of a standard dipole, allowing the antenna to stand upright |
| :--- | :--- |

| Main Use | Standard for VHF/UHF base stations, such as those used for emergency services and marine radio, to provide consistent coverage in all directions |
| :--- | :--- |
