<img width="628" height="492" alt="image" src="https://github.com/user-attachments/assets/d16307ed-a427-4d58-9083-70bb0062ebc2" />
<img width="473" height="432" alt="image" src="https://github.com/user-attachments/assets/f530bbd1-509c-42cb-a8a3-c9f9f2acb440" />
<img width="540" height="723" alt="image" src="https://github.com/user-attachments/assets/e03fef82-1ee4-48af-b84b-ae828f1f2ce8" />
<img width="428" height="166" alt="image" src="https://github.com/user-attachments/assets/0ac47d81-7c2f-48f1-9482-4e793bff2821" />
<img width="506" height="671" alt="image" src="https://github.com/user-attachments/assets/4c3ad606-358d-4f6b-9f91-966c7d10dfd3" />
<img width="411" height="268" alt="image" src="https://github.com/user-attachments/assets/cc10ddc8-d13d-46ab-aefe-e669159ce870" />
<img width="540" height="452" alt="image" src="https://github.com/user-attachments/assets/187d546a-1610-41f3-be80-9257edb8c72e" />








<img width="677" height="352" alt="image" src="https://github.com/user-attachments/assets/1fec952e-1ede-4ce1-bb85-54d3dd5c302d" />
<img width="713" height="643" alt="image" src="https://github.com/user-attachments/assets/c03a81c1-cdcb-439d-9abe-8af27b62247c" />
<img width="543" height="467" alt="image" src="https://github.com/user-attachments/assets/f5df131e-fe94-4eab-b565-e7d48eb05fad" />
<img width="707" height="473" alt="image" src="https://github.com/user-attachments/assets/cd04ef29-8f94-4be4-900f-29fd43d1932d" />


## LT spice circuit diagram

<img width="1863" height="844" alt="image" src="https://github.com/user-attachments/assets/e674b675-8640-4c4a-b723-ce941af22a50" />




## LT spice output graph

<img width="1863" height="844" alt="image" src="https://github.com/user-attachments/assets/aa3a9585-4a42-44f0-ab86-db8983c32496" />

## calculation
## Frequency Calculation

For a Wien bridge oscillator, when the two resistors and two capacitors in the frequency-selective network are equal:

- R9 = R10 = R
- C1 = C2 = C

The theoretical oscillation frequency is:

$$
f_0 = \frac{1}{2\pi RC}
$$

### Given Values

$$
R = 10\,k\Omega
$$

$$
C = 0.01\,\mu F
$$

Convert the values into SI units:

$$
R = 10\,k\Omega = 10,000\,\Omega
$$

$$
C = 0.01\,\mu F
$$

Since:

$$
1\,\mu F = 10^{-6}\,F
$$

Therefore:

$$
C = 0.01 \times 10^{-6}
$$

$$
C = 10^{-8}\,F
$$

### Theoretical Frequency

Substituting the values:

$$
f_0 = \frac{1}{2\pi(10,000)(10^{-8})}
$$

First calculate:

$$
RC = (10,000)(10^{-8})
$$

$$
RC = 10^{-4}
$$

Therefore:

$$
f_0 = \frac{1}{2\pi(10^{-4})}
$$

$$
f_0 = \frac{1}{6.283 \times 10^{-4}}
$$

$$
f_0 \approx 1591.5\,Hz
$$

Therefore, the theoretical oscillation frequency is:

$$
\boxed{f_0 \approx 1591.5\,Hz}
$$

or approximately:

$$
\boxed{f_0 \approx 1.59\,kHz}
$$

### Practical Frequency

The practical frequency is obtained from the LTspice transient waveform.

The frequency is calculated using:

$$
f_{practical} = \frac{1}{T}
$$

where:

- $T$ = measured time period of one complete cycle.

From the LTspice waveform:

$$
T = \text{[measured time period]}
$$

Therefore:

$$
f_{practical} = \frac{1}{T}
$$

$$
\boxed{f_{practical} = \text{[calculated frequency]} \, Hz}
$$
## result
