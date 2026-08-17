# Performance Analysis

The designed two-stage CMOS operational amplifier was evaluated in open-loop
and unity-gain closed-loop configurations using Cadence Virtuoso.

## Performance Parameters

| Parameter | Value |
|---|---:|
| Supply Voltage (VDD) | 1.8 V |
| Input Common-Mode Voltage | 0.9 V |
| Bias Current | 15 µA |
| Open-Loop DC Gain | 66.64 dB |
| Unity-Gain Bandwidth | 3.238 MHz |
| Phase Margin | 66.64° |
| Miller Compensation Capacitor | 5 pF |
| Load Capacitance | 0.2 pF |
| Slew Rate | 75 V/µs |
| Configuration | Unity-Gain Buffer |

## Slew Rate Calculation

The theoretical slew rate is calculated using:

**SR = I / CL**

where:

- I = 15 µA
- CL = 0.2 pF

Therefore,

**SR = (15 × 10⁻⁶) / (0.2 × 10⁻¹²)**

**SR = 75 × 10⁶ V/s**

Hence,

**SR = 75 V/µs**

## Stability

The phase margin obtained from the AC analysis is approximately **66.64°**,
indicating stable closed-loop operation with adequate stability margin.

## Summary

The two-stage CMOS op-amp achieves a DC gain of approximately 66.64 dB and
a unity-gain bandwidth of approximately 3.238 MHz. The phase margin of 66.64°
indicates satisfactory frequency compensation and stable operation when
configured as a unity-gain buffer.
