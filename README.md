# Renewable Energy Trainer Guided Lessons

Build a education prototype that uses current sensor, SD card, rotary encoder to lead learners through structured experiments. Include setup instructions, a circuit diagram, tested firmware, and sample output.

## Project details

| Field | Value |
| --- | --- |
| Roadmap ID | 1451 |
| Category | Education |
| Platform | Arduino Uno |
| Difficulty | Beginner |
| Estimated build time | 12 hours |
| Connectivity | USB serial |
| Core components | current sensor, SD card, rotary encoder |
| Control mode | interactive monitor |

## Repository layout

- `firmware/renewable-energy-trainer-guided-lessons/renewable-energy-trainer-guided-lessons.ino`: runnable firmware or application
- `docs/wiring.md`: suggested low-voltage wiring plan
- `docs/architecture.md`: system data flow
- `docs/test-plan.md`: repeatable verification steps
- `sample-data/example.json`: example telemetry record
- `tools/validate.py`: dependency-free repository validation

## Quick start

1. Open `firmware/renewable-energy-trainer-guided-lessons/renewable-energy-trainer-guided-lessons.ino` in Arduino IDE or Arduino CLI.
2. Select the board matching **Arduino Uno**.
3. Compile and upload, then open the serial monitor at 115200 baud.

## Expected behavior

Guided Lessons demonstration with repeatable test steps. The default implementation supports simulated or generic analog inputs so the control path can be exercised before hardware-specific drivers are added.

## Hardware adaptation

The included code is a safe reference implementation. Update pin assignments and sensor conversions from the exact component datasheets, then repeat the test plan before connecting actuators.

## License

MIT
