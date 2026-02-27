# PART 3: Phased & Multi-Element Arrays

---

# INTRODUCTION
While Yagi-Uda antennas use "parasitic" elements to focus a beam, Phased and Multi-Element Arrays take a more active approach. By feeding multiple driven elements simultaneously with specific timing (phase) and spacing, these arrays can create massive signal gain or even steer a beam electronically without moving the antenna itself. This section explores how arranging simple dipoles in grids or lines creates powerful, synchronized radiation patterns.

## ANTENNAS

## Broadside Array

<img width="471" height="272" alt="image" src="https://github.com/user-attachments/assets/d427ad25-676a-4089-877b-fb329987ca4e" />

A Broadside Array consists of several identical resonant elements, typically dipoles, arranged in a parallel line or a grid. All elements are fed with the same phase and magnitude of current, which causes the signal to radiate perpendicular to the plane of the elements. This creates a very wide but thin "fan" of signal that is bidirectional (firing both front and back).

| Distinct Physical Features | It features multiple λ/2 dipoles mounted side-by-side on a common frame. Physically, the spacing between each dipole is usually λ/2, and the entire structure looks like a large "ladder" or rectangular screen where the signal radiates "broadly" off the flat side |
| :--- | :--- |

| Main Use | Overseas broadcasting and maritime communications where a high-power signal needs to cover a wide geographical area |
| :--- | :--- |

## Combined Collinear Array

<img width="471" height="229" alt="image" src="https://github.com/user-attachments/assets/dd312f94-20b8-4fb3-96e0-3a3a8774bffc" />

The Collinear Array is essentially a "stack" of dipoles arranged end-to-end in a single vertical line. By placing elements on top of each other and feeding them in phase, the antenna flattens the signal toward the horizon, preventing energy from being wasted by shooting up into the sky or down into the ground. It provides $360^{\circ}$ coverage but with much greater distance than a single dipole

| Distinct Physical Features | It consists of multiple λ/2 elements placed in a single straight vertical line. Physically, it looks like a very tall, thin whip or pole, where each $\lambda/2$ section is connected by a phasing coil or "stubs" to ensure all segments radiate in unison |
| :--- | :--- |

| Main Use | Base stations for emergency services (Police/Fire), taxi dispatch, and cellular towers where omnidirectional coverage is required |
| :--- | :--- |


## Phased Array λ/4

<img width="471" height="213" alt="image" src="https://github.com/user-attachments/assets/66ec4604-7f56-42a7-94c8-0a2f6d74f81e" />

A Phased Array λ/4 uses two or more vertical antennas spaced a quarter-wavelength apart. By delaying the signal to one of the elements by $90^{\circ}$ (a quarter-phase), the signals cancel out in one direction and reinforce each other in the other. This creates a "cardioid" or heart-shaped radiation pattern that is highly directional.

| Distinct Physical Features | It typically consists of two vertical rods, each being λ/4 in height (a quarter of the wavelength). Physically, the footprint is small, with the two poles standing exactly λ/4 distance away from each other, often connected by a specific length of delay-line cable |
| :--- | :--- |

| Main Use | AM radio broadcasting stations that need to protect the signal of another station in a specific direction while boosting their own in another |
| :--- | :--- |


## Phased Array λ/2

<img width="471" height="292" alt="image" src="https://github.com/user-attachments/assets/9168738c-beeb-485b-b5f4-c13fe665744d" />


This array configuration spaces the driven elements a half-wavelength apart. When the elements are fed $180^{\circ}$ out of phase, the signal is cancelled along the line of the elements and reinforced in the perpendicular direction. This setup allows for much tighter control over the beam shape compared to smaller spacing, offering higher directivity.

| Distinct Physical Features | Like the λ/4 version, it uses vertical elements, but the physical gap between the poles is doubled to a full λ/2 distance. Each element is typically λ/4 vertical or λ/2 dipole, creating a wider physical footprint that results in a narrower, more focused beam |
| :--- | :--- |

| Main Use | Radar systems and sophisticated military communications where precise beamforming and interference rejection are critical |
| :--- | :--- |
