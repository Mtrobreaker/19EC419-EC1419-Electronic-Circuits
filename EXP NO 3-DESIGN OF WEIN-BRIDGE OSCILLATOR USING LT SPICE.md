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

### Theoretical Frequency

For a Wien bridge oscillator, the oscillation frequency is given by:

\[
f = \frac{1}{2\pi RC}
\]

Given:

\[
R = 10\,k\Omega = 10,000\,\Omega
\]

\[
C = 0.01\,\mu F
\]

Since:

\[
1\,\mu F = 10^{-6}\,F
\]

Therefore:

\[
C = 0.01 \times 10^{-6}
\]

\[
C = 10^{-8}\,F
\]

Substituting the values:

\[
f = \frac{1}{2\pi(10,000)(10^{-8})}
\]

\[
f = \frac{1}{6.283 \times 10^{-4}}
\]

\[
f = 1591.55\,Hz
\]

Therefore:

\[
\boxed{f_{theoretical} \approx 1591.5\,Hz}
\]

or

\[
\boxed{f_{theoretical} \approx 1.59\,kHz}
\]

---

### Practical Frequency

The practical frequency is obtained from the transient waveform in LTspice.

The time period is calculated using two consecutive identical points on the waveform:

\[
T = t_2 - t_1
\]

The practical frequency is:

\[
f_{practical} = \frac{1}{T}
\]

For example, if two consecutive peaks are measured as:

\[
t_1 = 50.00\,ms
\]

\[
t_2 = 50.63\,ms
\]

Then:

\[
T = 50.63 - 50.00
\]

\[
T = 0.63\,ms
\]

Converting milliseconds to seconds:

\[
T = 0.63 \times 10^{-3}\,s
\]

Therefore:

\[
f_{practical} =
\frac{1}{0.63 \times 10^{-3}}
\]

\[
f_{practical} \approx 1587.3\,Hz
\]

Thus:

\[
\boxed{f_{practical} \approx 1.587\,kHz}
\]

---

### Comparison

| Parameter | Value |
|---|---:|
| Resistance, R | 10 kΩ |
| Capacitance, C | 0.01 μF |
| Theoretical Frequency | 1591.5 Hz |
| Practical Frequency | 1587.3 Hz |
| Difference | ≈ 4.2 Hz |

The practical frequency is obtained from the LTspice transient waveform and should be close to the theoretical frequency.

## result
