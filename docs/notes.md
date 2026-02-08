# Project Notes – Off-Grid Inverter

## Objective
Design and simulate an off-grid inverter capable of converting DC battery
power into regulated AC output suitable for standalone loads.

## System Description
The system consists of a DC–DC boost converter followed by a PWM-controlled
H-bridge inverter. An LC filter is used at the output to reduce switching
harmonics and improve waveform quality.

## Control Strategy
- PWM generation for inverter switching
- Closed-loop voltage regulation
- Parameter tuning based on output stability

## Observations
- Stable sinusoidal output achieved
- Output voltage regulation verified in simulation
- Switching harmonics reduced using LC filter

## Limitations
- Simulation-only implementation
- No hardware validation

## Future Work
- Hardware prototype
- Efficiency optimization
- Advanced control strategies
