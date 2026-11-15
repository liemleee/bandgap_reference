# Low-Power CMOS Bandgap Reference

A low-power, all-CMOS voltage reference designed in GPDK090 (90 nm).
The circuit uses a two-stage PMOS-input OTA in its feedback loop and
combines CTAT and PTAT components to reduce output voltage drift
over temperature.

## Schematic-Level Simulation Results

| Parameter | Result |
| --- | --- |
| Design and simulation tools | Cadence Virtuoso / Spectre |
| Nominal supply voltage | 1.2 V |
| Reference voltage | ≈ 0.600 V |
| Temperature range | −40 °C to 100 °C |
| Reference voltage variation over temperature | ≈ 8 mV |
| Temperature coefficient | ≈ 95 ppm/°C |
| Minimum operating supply adopted in the report | 0.90 V |
| Phase margin | 95.77° |
| Startup time | ≈ 3.1 ms |

## Project Documentation

The [report folder](report/) contains the design report and presentation
slides. The report covers the circuit architecture, OTA design, and
schematic-level simulation results.
